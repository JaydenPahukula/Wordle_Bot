# Wordle_Bot

This bot will help you become the Wordle Master!

Wordle is a game made by NYT, in which you have to try and figure out the 5 letter word of the day. You have 6 guesses, and after each guess it will tell you which letters are correct (green/▓▓), correct but in the wrong place (yellow/▒▒), or just wrong (blank). Here are what all of my programs do:

**letterfrequencies.py** - this tool finds the frequencies of each letter in all possible words

**possibleanswers.txt** - this is all the possible answers to the Wordle game (NOTE: this is only used to make valid games, not to find solutions)

**possibleguesses.txt** - this is all the possible guesses you can make in a game of Wordle

**wordlebot.py** - run this program alongside your actual Wordle game and get invaluable reccommendations! Input your guess, then input the result as a string of numbers (Ex. green/yellow/grey/grey/yellow = 21001), and it will return guesses that will give you the most information, guesses that might be the solution, and their probabilities.

**wordlegame.py** - play a real, authentic game of Wordle!
