# Java-Wordle
Java-Wordle is a java implementation of the online game "Wordle".
(source https://www.powerlanguage.co.uk/wordle/)
It's like the board game "Mastermind" but with 5-letter words.
In this game, the user has 6 tries to guess a 5 letter word.
Each time the user guesses, the game returns an analysis.

In Java-Wordle that analysis looks like this:

* => Correct letter, correct place
~ => Correct letter, wrong place
_ => Wrong letter.

ex. 

if the answe was "ENTRY",
and the user guessed "TREAT",
then the analasys would look like this: "~ ~ ~ _ _"

if the answe was "PLACE",
and the user guessed "PIXEL",
then the analasys would look like this: "* _ _ ~ ~"
