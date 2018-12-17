# airhockey
An airhockey game

## Concept
There are two players and one puck. The players can move anywhere where they like on their half of the field.
The game is similare to pong.

You can play with either the keyboard (wasd and arrow keys) or with the controller (two controllers).

## Architecture
There is one main view in which the game runs. There are seprate views for every menu.

There is one controller. It renders the game model to the view. 
Every player has it's own model, as well as the puck.