<div id="top"></div>


## About The Project
Fully implemented chess game algorithm that supports:
* Human vs Human
* Human vs Computer / Computer vs Computer: AI Computer Player with 3 levels of difficulties
* Command line display
* Simple UI display using XWindow

### Built With
* C++
* Linux
* [XQuartz](https://www.xquartz.org)

### How to play
1. Start a game
    ```sh
    game [player1] [player2]
    ```
    `player` could be either `human` or `computer[1-3]`(`[1-3]` refers to the difficulty    level)
2. Make a move
    ```sh
    move [pos1] [pos2]
    ```
    for human player,
    ```sh
    move
    ```
    for computer player
## Demo Video
### Human vs Computer1
Level 1: The computer player will make a valid move

### Human vs Computer2
Level 2: The computer player will prefer to capture opponent's pieces

### Human vs Computer3
Level 3: The computer player will prefer to avoid capturing

### Human vs Human
https://user-images.githubusercontent.com/71295005/168456861-af6b094c-a8f2-4dfb-9f21-91d8f09e3c28.mov

