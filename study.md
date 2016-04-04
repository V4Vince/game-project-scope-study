# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss on Monday morning.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
  - How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code moodular.
-   What creative spin will you add to your project.
-   How you will use version control to backup / track your project.
-   Do you plan to attempt any of the bonuses.



Data Structure:
- Game Board: I will use a <div class=“game-board”> to represent the entire game board. And will use 9  <div class=“game-board squares> to represent the smaller squares in the board.

Then I will have jquery listen for a click event on the squares div. When the user clicks, jquery will add either a X div or O div to that clicked square.

When the game is over (X wins, O wins or Draw) jQuery will amend a <div class=“end-game”> which will display which player won across the screen. Player will then to able to choose “New Game” or “Quit” button.

Approach:
I plan to start building the structure of this game with HTML and make it look all nice with CSS. I will keep the HTML and CSS basic at first.

Then I will build in the functionality with JQuery and JS. I plan to first start building the code in one page. Then test the functionality. After all the basic features work, I will start to break up the code and modularize it.

User Story:
- As a user, I want to be able to click a square in the game board to make my moves
- As a developer, I will incorporate an easy click-to-play function

- As a user, I want to be able to leave a game before finishing and be able to pick off where I left off.
- As a developer, I will incorporate a login and logout feature to easily save games.

- As a user, I want to be able to keep track of how many times I’ve won and lost
- As a developer, I will incorporate a win and lose counter and increment accordingly after every win/loss

- As a user I want to be able to select between X or O
- As a developer, I will prompt the user to choose X or O at the beginning of the game.

Creative Spin:
I will allow users to select between different background themes.
I will also try to add in animations for when a user makes a play.

Version Control:
I will save and commit often. I will also include very good comments - promise.

Bonuses:
I don’t want to get ahead of myself. After I figure out how to get the basic requirements in, I would like to attempt to add a chat box and multiple player across device features.
