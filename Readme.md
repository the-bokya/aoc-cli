# Introduction

This is a really simple quick and dirty script made by me to make Advent of Code a little more accessible (atleast for me) through the command line.

## Usage

The format is

`./aoc <day> <action> <rest of the script's shit>   `
Valid arguments are: **"input"**, **"puzzle"** and **"submit"**.

1. **"input" gets the input for the puzzle:**
   
   This example fetches the input on the 23rd day and stores it in a text file named text:
   
   `./aoc 23 input > text`
   
   

2. **"puzzle" fetches the puzzle for the day and opens it in w3m if present:**
   This gets the puzzle for the 12th day: 
   
   `./aoc 12 puzzle`
   
   

3. **"submit" submits your answer to the selected level:**
   This submits your answer for the 2nd level of the 13th day as 1337:
   
   `./aoc 13 submit 2 1337`

## Notes:

1. You need to put your session into the session variable of the script for the script to work correctly.
2. It would be a good idea to put this script in your path for global accessibility.
3. Optionally, this script uses w3m and pup
