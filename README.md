# Pig Dice
Pig Dice Game Web Application, 2018/09/23
#### By *Gloria Givondo*
## Description
This is a web application that tries to assimilate the world of a Pig Dice Game. Two players can role a dice until the set target is achieved whereby the player who reaches the set target score is declared the winner and the game ends.
### Link to deployed site
https://gege-k.github.io/PigDice/
## Table of Content
1. [Description](#description)
2. [Behavior](#behavior)
3. [Installation](#installation)
4. [Bugs](#bugs)
5. [Support](#support)
6. [License](#license)
## BDD Specifications
| Behavior                          |  Input Example |  Output  Example|
|----------                         |:-------------: |------:          |
| Player 1 and Player 2 input names, and click start |  Player 1: Gloria / Player 2: Hamida / Click Game On    | Then starts the game |
|  Player 1 clicks Roll |  Click roll    |  Number is generated  |
|If Player rolls any number other than 1, roll is added to turn total   | Roll = 5     |  Turn Total =5    |
|If Player1 rolls 1, no score is added and round for Player 2  |  Roll = 1    |  Turn Total = 0, Score = 0,  Player2 plays    |
|If Player1 clicks Hold, turn total is added to his score and it's Player2 Turn | Click Hold     |  Turn Total = 5, Score = 5, Player2 plays    |
| When a player's total score is 100 or more, game is over and winner alert shows  |  Player 1 score = 105	    |  Gloria WINS     |
## Installation
### Installation Requirements
  git
  terminal
  Web browser
### Installation instruction
Run the command  ```git clone https://github.com/GeGe-K/PigDice.git ```
or
Download it from the repo ```https://github.com/GeGe-K/PigDice ```

```
  Extract the file
  Navigate to the file
  Open the index.html in your browser
  Enjoy the application
```
### Technologies used
HTML
CSS
Bootstrap
Javascript
JQuery
## Bugs
Currently the application runs perfectly fine without any issues.
## Support and Contact Details
If you encounter any issues, please reach out to gloriagivondo@gmail.com
### License
The content of this site is license under the MIT license
Copyright (c) 2018 **Gloria**
