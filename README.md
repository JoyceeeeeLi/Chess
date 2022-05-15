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
    game [white-player] [black-player]
    ```
    `player` could be either `human` or `computer[1-3]` (`[1-3]` refers to the difficulty level).
2. Make a move
    ```sh
    move [pos1] [pos2]
    ``` 
    for human player,
    ```sh
    move
    ``` 
    for computer player.
    
    
## Demo Videos
Note: On the chess board, pieces of `[white-player]` and `[black-player]` are distinguished by lower/upper case letters: <br />
         `[white-player]` - Lower case <br />
         `[black-player]` - Upper case <br />
### Human vs Computer1
* Level 1: The computer player will make a valid move when `move` command is executed.


https://user-images.githubusercontent.com/71295005/168457759-8cb06740-403b-4e50-8f47-41d80b96a70d.mov



### Human vs Computer2
* Level 2: The computer player will prefer to capture opponent's pieces. <br />

https://user-images.githubusercontent.com/71295005/168457856-af5c9ba9-9731-49c9-acb7-c662544ae504.mov

  We can see that computer player captured human player's pawn at d4.



### Computer3 vs Computer3
* Level 3: The computer player will prefer to avoid capturing. <br />
  This time let's try Computer player vs Computer player with Level 3 algorithm! <br />
  


https://user-images.githubusercontent.com/71295005/168458241-e977d0f1-519c-4108-922b-19a161084050.mov



We can see that Compter Player 1 avoid capturing from Computer Player 2's Knight at `a6` by moving pawn from `b4` to `b5`.


