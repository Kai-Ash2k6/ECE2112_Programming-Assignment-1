# ECE2112_Programming-Assignment-1
Advance Computer Programming - S.Y. '24-'25

Name: K. A. Gas*ng-n || Section: 2 ECE - C

----- Contents of this Assignment ----- 
    
    1. Alphabet Soup Problem - A program that sorts the letters of a word alphabetically
    2. Emoticon Problem - A simple program that replaces certain words with emoticons/emojis
    3. Unpacking List Problem - A program that shows the first element, the middle elements, and 
        the last element of the list    
---------------- Notes ----------------
    
    - I debugged my code multiple times and used module notes, YouTube tutorials, and 
      other online references to understand  concepts I was not confident with.
    - This repository is part of my journey in learning basic Python programming

 .... Analysis / Notes .....
    
    1. Alphabet Soup Problem
        - This program takes a string input and sorts its letters alphabetically.
        - The `sorted()` function converts the string into a list of characters and arranges them in ascending order.
        - The for-loop combines the sorted characters into a new string.
        - Generalization / Conclusion: This demonstrates how Python can manipulate sequences of data. Sorting can be applied to any iterable to 
            organize elements systematically, which is useful in text processing or data cleaning.

    2. Emoticon Replacer Problem
        - This program takes a text input and replaces specific words with corresponding emojis.
        - A dictionary `papalitan` stores the word-to-emoji mapping.
        - The program loops through each key-value pair and replaces all occurrences of the word (both lowercase and capitalized) with its emoji.
        - Generalization / Conclusion: This shows that string replacement can efficiently transform text data. The approach can be extended 
            to replace multiple patterns or for simple text-based data processing tasks.

    3. Unpacking List Problem
        - The first element of the list is stored in `first`.
        - The last element of the list is stored in `last`.
        - All elements between the first and last are stored in `middle` using the `*` operator.
        - Generalizarion / Conclusion: This shows that Python's unpacking feature allows us to separate a list into specific parts easily, which can be useful for 
            processing sequences of data.
  
-------------- How to run ------------- 
    
    1. Clone or download the repository
    2. Open the .ipynb file in Jupyter Notebook
    3. Run all cells in order to test the programs.
