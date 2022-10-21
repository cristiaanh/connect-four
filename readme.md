README.md




<title>CONNECT FOUR</title>

Technologies
-Javascript
-HTML
-CSS
-jquerey

wire frame skecth 

![wire frame sketch](wireframe.JPG)
PSEUDOCODE

-HTML
* Connect four as title at top of screen
* the current player displayed directly under
* A 6 by 7 connect four board with circles of the same dimension in the middle


-CSS
*the color of the board should be blue
*the chips the player drops into the board should be yellow and Red 
*the background should be black? or white? undecided
*connect four and current player should display as red 


-JAVASCRIPT
* function changePlayerTurn(){
    - check who is current player
    - switch from player 1 to player 2
    - run function for next action in game
  }

* function checkForWinner(){
    -check if a row of four has been completed
    -check if there is a tie

}

* function dropChip(){
    -check when each player has dropped there chip into the game board
    -see where that chip is in relation to the other chips on the board
    -NEED EVENT LISTENER
}

//link
https://cristiaanh.github.io/connect-four/

//screenshot
<img src="game screen shot.png" />

//instructions
-click on a circle in the board with the intention of getting your color (either red, or yellow) four in a row. You can acheive four in a row diagonally, vertically, or horizontally. Once you get four in a row, you win.

//future plans
-add background color and play around with font
-add animation of chips falling into the board
-make chips transparent
-give the game a theme..halloween, christmas etc.