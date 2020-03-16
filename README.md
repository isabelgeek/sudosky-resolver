# SUDOSKYNET SOLVER

What started as something to do the marking for sudokus ended up more often than not, entirely solving them.
Now available through siasky.net


## Intro
This is an interactive sudoku solver that uses only the following strategies to solve a sudoku puzzle (+ an easy to use interface).
* Row, Column or Block Singles.
* Naked Pairs.
* Naked Triples.
* Hidden Pairs.
* Hidden Triples.
* Pointing Pairs (or triples).

When ever a cell is entered by a user, the program sets to work figuring out candidates.

## How to use
* Use arrow and number keys to enter a sudoku.
* Click (d) for a demo.
* Click (c) to clear the board.
* Click backspace to delete.


## DApp URL
https://siasky.net/LAAW-FGPHXIjOo31FdUQIho1wxBt20rWaG5Gy-zARLz2LA


## Video Demo 
https://siasky.net/AAAlx-QPiEPleVjHQkzeEp-zzoJ-n2C33T0mAidh7moBlg


## Build the HTML
To build the html you can use the npm package `inliner`.
Tun the following commands and you will end up with a `dist.html` that contains everything which you can then upload to Skynet.
```
npm install -g inliner
cat index.html | inliner > dist.html
```

##  License
This application is released under the MIT License.

* Simple Sudoku Solver is released under the Open Source MIT License
Copyright (c) 2014 Andrew Hoyer https://github.com/ndrwhr

* MooTools http://mootools.net, A Compact JavaScript Framework.
Copyright © 2006-2020, Valerio Proietti & MooTools Developers.
MooTools libraries are released under the Open Source MIT License which gives you the possibility to use them and modify them in every circumstance.
