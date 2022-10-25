# Chapter 1 Exercises

Exercises with a tick mark :ballot_box_with_check: represent exercises that must be submitted as part of your Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.  


&nbsp;

## Exercise 1: Print Strings :ballot_box_with_check:

Write a Python program to print the following string in a specific format.

Twinkle, twinkle, little star,
	How I wonder what you are! 
		Up above the world so high,   		
		Like a diamond in the sky. 
Twinkle, twinkle, little star, 
	How I wonder what you are
#This is solution of exercise 1
print("Twinkle, twinkle, little star, \n\tHow I wonder what you are! \n\t\tUp above the world so high, \n\t\tLike a diamond in the sky. \nTwinkle, twinkle, little star, \n\tHow I wonder what you are")

## Exercise 2: Print the Version of Python :ballot_box_with_check:

 Write a Python program to get the Python version you are using.
#This is the solution of exercise 2
import sys
print("Python version")
print(sys.version)
print("Version info.")
print(sys.version_info)

## Exercise 3: Print date and Time :ballot_box_with_check:

Write a Python program to display the current date and time.
#This is the solution of exercise 3
import datetime
now=datetime.datetime.now()
print("Current date and time: ")
print (now.strftime("%Y-%m-%d %H:%M:%S"))

## Exercise 4: Strings Concatination :ballot_box_with_check:
Write three strings in different variables and print the output as one string.
&nbsp;
&nbsp;
&nbsp;
chocolate1= "Snickers"
chocolate2= "Godiva"
chocolate3= "Lindt"
print(chocolate1,chocolate2,chocolate3)

## Exercise 5: Compute area of Circle :ballot_box_with_check:

Write a Python program which accepts the radius of a circle from the user and compute the area.

&nbsp;
&nbsp;
&nbsp;
from math import pi
r=float(input("The radius of the circle: "))
print("The area of the circle with radius" + str(r)+ "is:" + str(pi*r**2))

