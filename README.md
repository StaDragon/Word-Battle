# Word Battle v2.1
INTRODUCTION
--------------------------------------------------------------------------------
Word Battle is a strategic word game situated around two or more players playing on a square board of arbitrary size between 3 and 15 with the objective of disabling every player from placing a word down onto the board to be the last player standing in order to win the game.


SETUP
--------------------------------------------------------------------------------
Ensure that you have downloaded Python 3.7 or 3.8 and PyCharm so that the game can be properly executed if run from there and for ease of installation of the all essential modules to run the game. Without these modules the game will crash.

The game includes the standard dictionary or lexicon of the English language.

**Disclaimer:**<br />
The language text file contains offensive language. There is no strict control that computer players on hard difficulty will not utilise them to win the game.<br />
There is no official rule dictating that offensive language are not to be played. However, in human vs human gameplay, it can be agreed upon to disallow the use of offensive language.

PLAYING THE GAME
--------------------------------------------------------------------------------
To begin playing the game, click on the run Word Battle.bat file and the game will be opened in an command prompt.<br />
Depending on your Python verion, you may run the program by clicking on the py file directly.


CHANGES FROM V1 TO V2
--------------------------------------------------------------------------------
The game engine has been overhauled.<br />
All the text in the game is now more brighter.<br />
As multi-language is no longer supported, the text file "Language" is renamed to "English".<br />
The game no longer crashes when a text file is not found in the game's folder, the game will now display an error message instead.<br />
The game will now display an error message instead of displaying the cmd's README when the game's README text file is not found in the folder.<br />
The "Play Game" option is now split into two options, "Play vs Human" and "Play vs Computer".<br />
When notified about full paths, all of those paths will now be highlighted red to reveal its location.<br />
There is now a comma between the words used.<br />
The metadata of .wbr files has changed and now has basic encryption to make its content less accessible.


NEW IN V2
--------------------------------------------------------------------------------
Game duration is now displayed at the end of the games and during the replays.<br />
You can play against more than one computer player.<br />
You can watch more than two computer players playing against each other.<br />
Each computer player now have their own difficulty setting and their own vocabularies (which are dependent on their difficulty).<br />
You can now view the game from the computer player's perspective by uncommenting the self.turn_visualisation() code in the Agent class under the play method.<br />


UPDATE V2.1
--------------------------------------------------------------------------------
Board UI has been improved.


NOTES
--------------------------------------------------------------------------------
Do not use the "Language" text file as it can no longer be read by the game, use the "English" text file instead.<br />
Do not open old .wbr files as they can no longer be read by the game.


BUG FIXES
--------------------------------------------------------------------------------
**22/09/2020**
Minor bug fixes.


CONTACT INFORMATION
--------------------------------------------------------------------------------
If you have any questions, feedback or if you experience any bugs or issues when running the program, feel free to contact me at stadragondev@gmail.com.

LICENSE
--------------------------------------------------------------------------------
Please view LICENSE.md
