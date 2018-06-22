## Fusion
Fun mind teasing puzzle game

## How to install? [Linux]

* Install dependencies
    * `sudo apt-get install libx11-dev`
* Open terminal in this directory
    * `make` to compile code [creates an executable **fusion**]
    * `make play` or `./fusion` to start playing

## How to play?
* The game board is circular
* An element (from periodic table if you remember) pops up in the center
* It can be placed anywhere on the circular board
* As it is placed a new element appears in the center again
* Sometimes a special element pops up which can fuse other elements, say `+`
    * The fusion occurs on pairs of elements on either side of the fusing element
    * For Ex. `H` `+` `H` -\> `He`
    * More than one pair of elements can be fused at a time
    * For ex: `Li` `H` `+` `H` `Li` -\> `Be`
* Not more than a **fixed number of elements** can be present on board
* Plan place fuse and repeat to score the highest

## Credits
Inspired by Atomas game in Google Play Store
