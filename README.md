# spellChecker

# How it works

This is a very basic spellchecker writen in python it works by takeing in a text document of words and converts those to numbers based on what keys are closest on the keyboard and their for most likley to be miss typed then in converts that word that you wrote to those same number and after going through the dictionary it find the most likley word from the list and print that.

# How to use

If you run 'python3 spellchecker.py' it will enter a loop where you can type in a word or words and it will try and correct them and then it will let you type more in.
Or you can pull everything into a file and run 'python3 spellchecker {inputFile}' and it will take everything in that file, it will check it and then output a output.txt file of the corrected words. (Warning this might take a super long time)

# Why

It was an idea that I had where you could use commonly miss pressed key to correct those and use that to help a better spellchecker find that word you were trying to type but this project is very surface level.

# Where I got the data

If you are wondering where I got the word data I did not make it myself I got it from the website "https://norvig.com/ngrams/" I used sowpods.txt and I converted it to lower.

# Weak points

Pretty much everything, it's not really good at anything and mosly if the words are of different length. Also the source data has a lot of bad data in it.

# inprovment

There are many inprovements but I am going to try to focus on inprovements along the line of the ideas of this involving math to find commonly incorrect words and often mistyped letters ect.

Rethink the way to asign to number like more along most commonly missed typed letters instead of somewhat closness on the keyboard.

Add multithreading if there is more than one word.

add more prob
