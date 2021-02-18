# Feb-March 2021 Challenge
If you're confused on how to do something, just ask me!

You can earn points by submitting solutions for any of the problems, so don't worry about finishing all of them if you can't yet.

<b>Please</b> create a separate file for each problem you submit to Google Classroom.

## Leaderboard

| Contestant | Current score | Problem 00| Problem 01| Problem 02| Problem 03| Problem 04|
|-|-|-|-|-|-|-|
| Samir Rajani | 14 | | | | | |
| Jon Jazwinski | 3 | | | | | |
| Jack Donofrio | N/A | | | | | |

## Problem 00
Given three daily temperatures, return the three-day average.
``` 
Monday: 40F
Tuesday: 42F
Wednesday: 46F
```

## Problem 01
There are 60 seconds in a minute, 60 minutes in an hour, and 24 hours in a day. Compute the number of seconds in 2 days.

## Problem 02
Water boils at 100&deg;C. Write a program that takes the temperature as an input value and prints whether or not water will boil at that temperature.

Here's a little guide on taking user input if you're unfamiliar:
``` Python
# Waits for user to enter a value, then stores it in name.
name = input()

# Displays "What is your name?" and waits for the user to enter a value to store.
name = input('What is your name?') 

# The input() function stores values as strings, so if you want to take integer inputs, you
# will have to convert the string to an int using the int() function
age = int(input('What is your age?'))

# The line above displays 'What is your age?', waits for user input, then converts it to an int to store

# So for this problem, you can get the temperature by using
temperature = int(input('Enter the temperature?'))

# If you want to take in floating point (decimal) numbers instead of just integers, use float() instead of int()
temperature = float(input('Enter the temperature?'))
```

## Problem 03
All triangles have three sides: A, B, C.

Triangles can only be considered valid if the following conditions are met:
``` Python
A + B > C
A + C > B
B + C > A
```
Write a program that takes in three side lengths, A, B, C, as user input, and prints whether the triangle is valid.

## Problem 04
Take a number as an input and print "Odd" if it's an odd number and "Even" if it's even.
``` Python
# Hint: The Modulo operator (%) returns the remainder of dividing two numbers.
# Example:
print(5 % 2) # Displays 1, because 5 / 2 equals 1 with a remainder of 1
print(9 % 3) # Displays 0, because 9 / 3 equals 3 with 0 remainder

# To check whether one number is divisible by another,
print(15 % 5 == 0) # Displays True, because 15 / 5 is 3 with 0 remainder, so 15 % 5 returns 0, which meets the condition
```
