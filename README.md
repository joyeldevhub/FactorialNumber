# FactorialNumber
Program to find the Factorial of a Number.
Explanation:
============
The program starts with the declaration of the package org.javainterview.

Next, the FactNum class is defined. This class contains the logic to calculate the factorial of a given number.

Inside the FactNum class, there is a private method called num(). This method is responsible for taking input from the user, calculating the factorial, and displaying the result.

Within the num() method, a Scanner object named scan is created to read input from the user.

The program prompts the user to enter a number by displaying the message "Enter the Number: ".

The entered number is read using the nextInt() method of the Scanner class and stored in the num variable of type int.

One additional variable is declared: fact, which is initialized to 1. This variable will hold the factorial of the input number.

A for loop is used to iterate from 1 to the entered number (num).

Inside the loop, the value of the fact is updated by multiplying it with the loop variable i.

After the loop finishes, the program displays the message "Factorial of your number is: " followed by the value of a fact, which is the factorial of the entered number.

The main method is declared, which is the entry point of the program.

Inside the main method, an instance of the FactNum class is created using the statement FactNum info = new FactNum();.

The num() method is called on the info object to start the factorial calculation process.

The program execution ends.

==> In summary, this program prompts the user to enter a number, calculates it's factorial using a for loop, and displays the result. The factorial of a non-negative integer n is the product of all positive integers less than or equal to n. <==
