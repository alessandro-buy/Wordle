# Wordle Solver
I decided to write an algorithm to attempt to solve the Worlde of the day in as little guesses as possible. 

If you are not familiar with Wordle of the Day, see the New York Times website here:
https://www.nytimes.com/games/wordle/index.html

Basically, the objective of the game is to guess a 5-letter word within 6 guesses.
Each time you guess a valid 5-letter word, the site tells you information about your guess. For each letter in your guess, 
Wordle tells you whether the word is A) Not in the Word, B) In the word but in the wrong place, or C) In the right place.

To run this file, you will need an environment like Anaconda to run Jupyter Notebooks in. 
Then, simple Shift+Enter through all the cells of code to start solving the Wordle.

From my own testing, I've discovered that the average amounts of guesses the algorithm takes is between 3 and 4. (Closer to 3 depending on the starting word)
My algorithm also believes the best starting word to use out of the possible answers is RAISE. 

When using RAISE as a starting word, Wordle was able to solve the puzzle in 6 guesses 999 times out of 1000 words. 

Not all starting words will guarentee success, but the Wordle Solver should be ok with any of the famous openers (CRANE, TEARS, TARES, STARE, RAISE, ARISE, ADEIU, etc)
