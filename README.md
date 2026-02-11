      PROJECT DESCRIPTION 
This project is a simple JavaScript program that analyzes a sentence entered by the user. The sentence must end with a period (.). The program calculates:
The total number of characters
The total number of words
The total number of vowels
The results are displayed using both console.log() and an alert message.

       HOW IT WORKS 
The user is prompted to enter a sentence that ends with a period (.).
The program reads the sentence character by character.
  It counts:
    Characters (including spaces and the period)
    Words (separated by single spaces)
    Vowels (a, e, i, o, u in both lowercase and uppercase)
The program stops processing once it reaches the period.
The results are displayed on the screen.

        Algorithm Logic
Three counters are initialized:
    charCount → Counts total characters
    wordCount → Counts total words
    vowelCount → Counts total vowels
A flag variable inWord is used to detect word boundaries.
The program loops through each character in the sentence:
    Increments the character counter
    Checks for vowels
    Detects spaces to count words
    Stops when it encounters a period (.)



      
