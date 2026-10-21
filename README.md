# PYTHON-FUNDAMENTALS-ASSIGNMENT-1_DATA-STRUCTURES-STRINGS-AND-TUPLES

Python Assignment 1: Data Structures - Strings & Tuples

Strings (Concatenation, Slicing and Other methods) :

1. String Concatenation:
Write a Python program that takes two strings i.e string 1 “Hello ”, string 2 get name as
input from the user and concatenates them together.

Display the concatenated string as
the output.

Sample Output:

Enter your Name: Zara

Hello Zara

Now concatenate string 3 “, welcome to Python programming” to the existing string and
display the output string.

Sample Output:

Hello Zara, welcome to Python programming

2. String Slicing and Indexing:
   
Write a Python program using the above concatenated string as input and performs the
following tasks:

a. Print the first character of the string.

b. Print the last character of the string.

c. Print the first 5 characters of the string.

d. Print the last 11 characters of the string.

e. Print the string in reverse.

f. Use slicing and print the word “Python” from the existing string.

4. String Methods:
Write a Python program that takes a string, strM = “Python beginner tutorial” and
perform the following tasks:

a. Convert the sentence to uppercase.

b. Convert the sentence to lowercase.

c. Use Capitalize and return the sentence to the original input form.

d. Count the total number of occurrences of character ‘t’ in the string.

e. Replace all occurrences of “Python” with “Machine Learning” in the input string
strM = “Python beginner tutorial”

Tuples (Creation, Modification and Access) :

Create 1st tuple with values -> (10, 20, 30), 2nd tuple with values -> (40, 50, 60):

a. Concatenate the two tuples and store it in “t_combine”

b. Repeat the elements of “t_combine” 3 times

c. Access the 3rd element from “t_combine”

d. Access the first three elements from “t_combine”

e. Access the last three elements from “t_combine”


# PYTHON ASSIGNMENT 2: DATA STRUCTURES - LIST,DICTIONARY,SET & CONDITIONAL STATEMENTS

# List (Creation, Modification and Access):

# 1. List Creation:

a. Create a list named age_list with five integer elements. For eg., [24, 25, 26, 27, 28]

b. Create a list named name_list with five string elements.

# 2. List Operations / Modifications:
   
a. Append the string "Yazhini" to name_list.

b. Insert the element 30 at index 2 in age_list.

c. Remove the string "Yazhini" from name_list.

d. Pop the last element from age_list.

e. Extend the age_list with additional ages [29, 30, 26].

f. Sort age_list in descending order.

g. Find Max age, Min age and sum of all ages from age_list.

# 3. Accessing List Elements:

a. Print the first element of name_list.

b. Print the last element of name_list.

c. Print the elements from index 2 to index 4 in name_list.

d. Print the elements of name_list in reverse order.

# Dictionary (Creation, Modification and Access):

a. Create a dictionary named student_marks that maps the names of five
students to their marks (use scale of from 0 to 100).

b. Access and print the mark of a specific student, of your choice.

c. Add a new student "Janani" with a mark of 80 to the student_marks dictionary.

d. Update the mark of any one older student to 82.

e. Use the keys(), values(), and items() methods to print all keys, values, and
key-value pairs in the student_marks dictionary.

# Sets (Operations):

a. Create a set called my_set with following values:

['a','e','i','o','u','a','a','i']

Analyse the output and provide explanation for the same.

b. Attempt to change the value of my_set[4] = 's'. If code throws an error, provide
an explanation.

c. Create two sets:

   set1 with values: {1, 3, 5, 7, 9}

   set2 with values: {2, 3, 5, 8, 10}

d. Compute and print the union and intersection of set1 and set2.

# Operators & Conditional Statements :

(IF, ELIF, ELSE)'

Performance Category Program:

1. Prompt user for Input. Score range should be from 0 to 10 (both inclusive).
   
2. Find the performance category based on the input score using following criteria:
   
a. Above Average: Score greater than 7

b. Average: Score between 4 and 7(both inclusive)

c. Below Average: Score lesser than 4

3. Output: Print the Performance category
   
4. Additional Step: You can give a prompt of your choice to each category.
For eg: If score below average “Need to Improve your performance, consistent
practice will lead to better results”.


# PYTHON ASSIGNMENT 3: WHILE LOOP, FOR LOOP AND FUNCTION

**While loop & Control Statements :**
(else, break, continue, pass)

*Number Guessing Game*

Problem Statement: Create a Python program that implements a simple number
guessing game using a while loop. The program should make use of control
statements such as else, break, and continue.

Instructions:
1. Set Up the Game:

★ Generate a random number between 1 and 10 that the user has to guess.
Import random and use randint function.

import random

# Generate random number between 1 and 10

secret_number = random.randint(1, 10)

2. Prompt the User:
 
★ Ask the user to guess the number.

★ Set a variable attempts to 3, which represents the maximum number of
guesses allowed.

3. Implement the Guessing Logic:
   
★ Use a while loop to allow the user to keep guessing until they get the
correct number or run out of attempts.

★ Provide feedback to the user for each guess:

➢ If the guess is out of the valid range (1 to 10), inform the user.

➢ If the guess is greater than the secret number.

➢ If the guess is lower than the secret number.

➢ If the guess is correct, congratulate the user and end the game.

4. Control Statements:
   
★ Use continue to skip the rest of the loop after informing the user if the
guess is out of range.

★ Use break to exit the loop when the guess is correct.

★ Use else with the while loop to provide a message like "Better luck next
time!" if the user runs out of attempts without guessing the correct number.

Sample Output:

Guess the number (between 1 and 10): 2

Too low. Try again.

Guess the number (between 1 and 10): 15

Your guess is out of range. Please guess a number between 1 and 10.

Guess the number (between 1 and 10): 5

Too high. Try again.

Guess the number (between 1 and 10): 3

Congratulations! You guessed the correct number.

**For Loop:**

*Multiplication Table Generator*

Problem Statement: Create a Python program that generates and prints a
multiplication table (from 1 to 10) for a given number using a for loop and the range
function.

Step wise Instructions:

1. Prompt user for Input. Ask the user to enter a number for which they want to
generate a multiplication table.

2. Generate the Multiplication Table: Use a for loop to iterate through the numbers
1 to 10. In each iteration, calculate the product of the user's number and the
current number from the loop.

3. Display the Multiplication Table:
Print each line of the multiplication table in the format: "number x i = result".

Sample Output:

Enter the number for which you want the multiplication table: 5

5 x 1 = 5

5 x 2 = 10

5 x 3 = 15

5 x 4 = 20

5 x 5 = 25

5 x 6 = 30

5 x 7 = 35

5 x 8 = 40

5 x 9 = 45

5 x 10 = 50

**Function:**

*BMI Calculator*

Problem Statement: Create a Python program that calculates the Body Mass Index
(BMI).

Hint: BMI = weight (kg) / [height (m)]2

Instructions:

1. Define a function calculate_bmi(weight, height) that returns the BMI.
   
2. Prompt the user for their weight (in kg) and height (in meters).
   
3. Use the function to calculate and display the BMI

Sample Output:

Enter your weight in kg: 58

Enter your height in meters: 1.62

Your BMI is: 22.10
