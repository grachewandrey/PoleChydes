# PoleChydes
This is a game in which the player is going to guess the word.

**Title: "Pole Chydes"**
Description, rules and mechanisms of the game: This is a game in which the player is asked to guess the word.
One letter of the alphabet is given by the player, and if such a letter is present in the word, it becomes opened on a screen.
The screen is a set of asterisks, the number of which equals to the length of the word.
If the player gave the wrong guess, the message "You did not guess the letter" is displayed, and a new letter guess is offered to the player.
In the case when the player named the word by a letter or guessed the whole word, the word itself is displayed and a message about the victory is shown along with the number of attempts made.

**Game features, commands used, other peculiarities:**
- Input is required by one letter or by the whole word
- It is possible to call up The Help Window for the game by writing the command "!help"

**Technologies in the project:**
- The Help Window is implemented using a separate function in the project code
- The project uses random selection "random.choice" of one word from the "start_word_1" tuple
- There is a formation of a "mask" of the word consisting of the symbol "*". The length of the mask is based on the number of letters in the word. 
