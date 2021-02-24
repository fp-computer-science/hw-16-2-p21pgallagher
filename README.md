<h1 align="center">
    Fairfield College Preparatory School<br>
    Computer Programming - Mr. Mesquita<br>
    HW 16-2
</h1>

<h2 align="center">Due before 8:30 AM on 2/15 (10 pts.)</h2>

### Writing Files
---
Answer each of the following questions in a separate Python file named `hw16-2-#.py` where `#` is the number of the question. In your heading, put your name and the date you began working on the file. (5 pts. each)

1. Modify the program from question 1 in HW 16-1 so the output is written to a file called `alice_word_frequency.txt` instead of printing it to the console. The word frequency table should remain the same, with the exception of not including the longest word at the end.

2. Write a program that prompts the user for the name of a text file and produces an output file which is a copy of the original file, but with line numbers. The new file should be called `copy_filename.txt` where `filename.txt` is the name of the original file. The first four characters of each line in this new file should be a 3 digit number followed by a space. Be sure to start your numbering at `001` adding leading zeros to numbers that are not 3 digits long. Use any of your previous assignments to test the program.

    Sample Input: `Enter the path to a text file on your computer: alma_mater.txt`
    
    `alma_mater.txt`
    ```
    Fairfield Prep full rich in beauty,
    Rising from the sea,
    Mother of delight and duty,
    Hear our pledge to thee!
    Deeper than the Sound's blue water,
    Stronger than the gale,
    Is our love for Alma Mater,
    Fairfield Prep, all hail!

    ```

    Sample Output: 
    
    `copy_alma_mater.txt`

    ```
    001 Fairfield Prep full rich in beauty,
    002 Rising from the sea,
    003 Mother of delight and duty,
    004 Hear our pledge to thee!
    005 Deeper than the Sound's blue water,
    006 Stronger than the gale,
    007 Is our love for Alma Mater,
    008 Fairfield Prep, all hail!
    009 
    ```

<p align="center">Be sure to commit your code before the deadline. Only the latest commit will be graded.</p>
