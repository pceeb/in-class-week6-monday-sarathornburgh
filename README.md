## In class exercise

1. If you wanted to reuse this program for a file that had 17 headers lines. What line of code
would you change in our program?

        Write the line of code that you will replace here: if LineNumber > 0:

        What will be the new code? the new code will skip to the 18th line instead of the 2nd line

        Write the new code here: if LineNumber > 16:

2. What would happen if we don’t included `import sys` in our program?

        Write you answer here: All commands needed that use the 'sys' program such as sys.argv would not work.

3. Let’s suppose that the third file that the user provides as input
has only one column. What error message will be generated?

        Write you answer here: Line 1 not XY format in file 3
        

4. Our program split lines of input files (except the first file) into elements
that are tab delimitated. However, data could be split by `,` or many other
characters. In this case is a good idea to define a new variable that takes the delimiter
provide by the user. Using what you learn about `sys.argv` in this class`.
Write a variable that reads a delimiter (e.g ',') provided as the first input file.

        Write your code here: replace ElementList = Line.split('\t') with ElementList = Line.split('v') and have the user assign the variable v to whatever delimeter they desired at the beginning of the code.
