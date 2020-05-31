# RAIInet
CS246 Group Project
RAIInet is a game played between two opposing players, who take on the role of computer hackers. Each player controls eight pieces, called links. 
There are two different kinds of links: viruses and data. 
Each player has two goals:
1. Download four data
2. Make the opponent download four viruses
Upon achieving either goal, the player wins the game.

To play this game, simply clone this repository, use the "make" command to compile and then run the game with the command ./RAIInet

There are a few parameters that players can set up before the game starts:
  -ability1 <order>
  -ability2 <order>
  -link1 <order>
  -link2 <order>
  -graphics: an indicator of whether a graphical display is wanted during the game
  -sleep: an indicator of whether a short paulse between turn switches is wanted

An example of setting up parameters look like:
  ./RAIInet -ability1 LFDSP -ability2 LFSDP -link1 V1V2V4V3D1D2D3D4 -graphics
 
 
There are a few text-based commands players can use during the game:
  move <A> <dir>
  abilities
  ability <N>
  board
  sequence <file>
  quit
 
 For a detailed description of the above commands and parameters, please refer to the "RAIInet.pdf" file.
 
 Enjoy playing!
 
