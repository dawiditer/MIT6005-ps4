# [Problem Set 4: Multiplayer Minesweeper](https://ocw.mit.edu/ans7870/6/6.005/s16/psets/ps4/)
## Overview
You will start with some minimal server code and implement a server and thread-safe 
data structure for playing a multiplayer variant of the classic computer game “Minesweeper.”

* You can review the [rules of traditional single-player Minesweeper on Wikipedia.](http://en.wikipedia.org/wiki/Minesweeper_(video_game))

* You can also [play traditional single-player Minesweeper online .](http://minesweeperonline.com/)

(You may notice that the implementation in the latter link above does something subtle. It ensures that there’s never a bomb where you make your first click of the game. You should not implement this for the assignment. It would be in conflict with giving the option to pass in a pre-designed board, for example.)

Your final product will consist of a server and no client; it should be fully playable using the telnet utility to send text commands directly over a network connection as described below.
