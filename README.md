# Python
This repository stores my various projects done using Python programming language. In this README file, I inted to explain my thought process while writing the code for each project, in order to make the project easier to understand for myself, as well ass others.
**#Project 1- Calculator (CLI)**
Introduction: Here, I've created a simple command-line calculator that performs basic arithmetic: Addition, subtraction, multiplication and division. 
Code Explanation: 
First of all, I've defined the exact operations that the calculator needs to perform, in the form of functions. While there are no exceptional cases in Addition, Subtraction or Multiplication, I've included an expceptional case in the divide(x,y) function, that is, division by 0. This ensures that, if the input specifies the division of any number by zero, thenit would return an Error message (modified).
Then comes the part of what is seen by the user in the beginning. So, using a series of print() statements, I've stated the 4 types of oerations that this calculator can perform, urging the user to choose their preferred operation. 
Then, I've used input() statements to take user input, and specified the accepted datatype for the two numbers to be entered. 
After that, I've linked the various operations, defined in the form of functions in the beginning, to their respective input values, or input operators, by the user. In case the user enters any choice other than the four mentiooned operators (+ - * /), then it will print "Invalid operator".
Finally, it will print the result of the operation as chosen by the user.

