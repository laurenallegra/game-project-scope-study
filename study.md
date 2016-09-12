# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

(wireframe pics are in adjacent tab)
`./tic-tac-toe-wireframes.jpg`

DATA STRUCTURE
I plan to use a data structure as following:
For users, I will use an id, an email, a password, and a token.
For the game itself, I plan to use an id, cells, a gameboard, and players
represented by the letters 'x' and 'o'.

REPRESENTATION OF GAMEBOARD IN JS
I plan to use a zero-indexed array of nine empty strings to represent the
gameboard, with each empty string representing a cell in the tic-tac-toe board
(ie, 0 = top left, 1 = top middle, and so forth).

APPROACH
My approach for our first project is simple: create a straightforward,
intuitive, and visually pleasing tic-tac-toe game as an SPA that meets course
requirements (LINK HERE). While I am learning a lot along the way, I still have
a few features left to work on that I plan to execute when I resubmit.
Unfortunately, I am a still a relatively slow (but diligent!) programmer, and I
was not able to meet all preoject requirements in the time allotted.
Items I will implement are listed in the TODO below.

USER STORIES
  -As a user, I want to be able to sign up.
  -As a user who has already signed up, I want to be able to sign in.
  -As a user, I want to be able to change my password.
  -As a user, I want to know that my password is being stored securely.
  -As a user, I want to play a game of tic-tac-toe.
  -As a user, I want to be notified when X or O wins, and which one, or if there
   is a tie.
  -As a user, I want to have the wins, losses, and ties associated with my
  username appear in the browser.
  -As a user, I want to interact with a visually pleasing UI that is easy to
  understand and intuitive.

PLAN TO KEEP CODE MODULAR
I will try to implement a rough separation of concerns by following naming
conventions for files and folders that we have learned in class. I will try to
use my `main.scss` as a 'manifest' for additional css files like colors, themes,
and typography.

CREATIVE SPIN
The idea of making the game-board look sort of hand-drawn is appealing to me,
since tic-tac-toe is usually a game played scrawled on a piece of paper. I think
the visual approach should be simple and maybe include a little silliness...
which is what playing tic-tac-toe feels like to me!

VERSION CONTROL PLANS
I will use git to track my progress, and try to make small cohesive commits with
good commit messages. I will try to use different branches to work on different
features, a process that is new to me.
BONUSES
I will be very pleased if I meet requirements! So no bonuses for now, but I
would like to take time later on to improve my html and css styling, as I am
relegating those concerns to the back-burner so that I can focus primarily on
javascript in the time allotted for the project.

UPDATE:
After working dilligently on the project, I still have a few things left to do.
I will seek help from an instructor to accomplish meeting requirements. Also,
when I have time, I will work on items from the list below to improve this first
project until it is a piece of my portfolio I am pleased with.

TODO
-make my code more DRY
-improve CSS for a better UI (eg, hide sign-in/password buttons after sign-in,
make page layout less vertical, etc.)
-experiment with modals for sign-up, sign-in
-implement more semantic html tags (ie, avoid using divs whenever possible)
-separate css concerns by placing styles in 'themes', 'typography' files
-store colors in `$font-color, etc names for better DRY code
-update game logic to reflect wins/losses/ties counter (currently static)
-update current game logic to reflect tie conditions (bug fix)
-make app responsive by adding breakpoints
-clean up my code by making it more readable and removing unnecessary code
blocks or commented-out lines
-improve the logic of my folder and file system with more files and enhanced
naming conventions
