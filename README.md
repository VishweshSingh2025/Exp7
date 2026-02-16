AIM
To study and implement decision-making and problem-solving in Python using conditional statements and logical operations to perform real-world computations and validations.

_______________________________________________________________________________________________

THEORY
Conditional statements in Python are used to control the flow of program execution based on specific conditions. The if, elif, and else statements allow a program to make decisions by evaluating logical and relational expressions. These statements help in executing different blocks of code depending on whether a condition is true or false.

Conditional logic is commonly used in applications such as number classification, grading systems, salary and tax calculations, validation of inputs, and date manipulation. Python supports relational operators (>, <, >=, <=, ==, !=) and logical operators (and, or, not) to form complex conditions. By combining these operators with conditional statements, programs can handle real-life scenarios efficiently and accurately.

_______________________________________________________________________________________________

ALGORITHM 1: DISPLAY NUMBERS FROM 1 TO N USING WHILE LOOP

Start

Input a number n from the user

Initialize a variable i with value 1

Check whether i is less than or equal to n

If true, display the value of i

Increment i by 1

Repeat steps 4 to 6 until the condition becomes false

Stop

_______________________________________________________________________________________________

ALGORITHM 2: FIND FACTORIAL OF A NUMBER USING WHILE LOOP

Start

Input a number n from the user

Initialize a variable fact with value 1

Check whether n is greater than 0

If true, multiply fact by n

Decrease the value of n by 1

Repeat steps 4 to 6 until n becomes 0

Display the factorial value

Stop

_______________________________________________________________________________________________

ALGORITHM 3: GENERATE FIBONACCI SEQUENCE USING WHILE LOOP

Start

Input the number of terms n from the user

Initialize variables a = 0 and i = 1

Initialize a counter variable terms = 1

Check whether terms is less than or equal to n

Display the value of a

Calculate c = a + i

Assign a = i

Assign i = c

Increment terms by 1

Repeat steps 5 to 10 until the condition becomes false

Stop

_______________________________________________________________________________________________

ALGORITHM 4: GENERATE FIBONACCI SEQUENCE UP TO A GIVEN LIMIT

Start

Input the limit value from the user

Initialize variables a = 0 and i = 1

Check whether a is less than or equal to the limit

Display the value of a

Assign new values as a = i and i = a + i (previous values)

Repeat steps 4 to 6 until a exceeds the limit

Stop

_______________________________________________________________________________________________

ALGORITHM 5: FIND THE REVERSE OF A NUMBER USING WHILE LOOP

Start

Input a number n from the user

Initialize a variable rev with value 0

Check whether n is greater than 0

Find the last digit using digit = n mod 10

Update rev as rev = rev × 10 + digit

Remove the last digit from n using integer division by 10

Repeat steps 4 to 7 until n becomes 0

Display the reversed number

Stop

_______________________________________________________________________________________________

ALGORITHM 6: CHECK WHETHER A STRING IS A PALINDROME

Start

Input a string from the user

Initialize two variables: i = 0 and j = length of string − 1

Check whether i is less than j

Compare the characters at positions i and j

If the characters are not equal, display “Not a Palindrome” and terminate the loop

Else display “Palindrome” and terminate the loop

Stop

_______________________________________________________________________________________________

ALGORITHM 7: CHECK WHETHER A STRING IS A PALINDROME USING STRING REVERSAL

Start

Input a string from the user

Create the reverse of the string

Compare the original string with the reversed string

If both are equal, display “Palindrome”

Else display “Not a Palindrome”

Stop

_______________________________________________________________________________________________

ALGORITHM 8: COUNT THE NUMBER OF DIGITS IN A NUMBER

Start

Input a number from the user

Initialize a variable count with value 0

Check whether the number is greater than 0

Divide the number by 10 using integer division

Increment count by 1

Repeat steps 4 to 6 until the number becomes 0

Display the value of count

Stop

_______________________________________________________________________________________________

ALGORITHM 9: SEARCH AN ELEMENT IN A LIST USING WHILE LOOP

Start

Create a list containing elements

Input the element to be searched (key)

Initialize index variable i = 0

Check whether i is less than the length of the list

Compare the element at index i with the key

If both are equal, display the index position and terminate the loop

Else increment i by 1

Repeat steps 5 to 8 until the element is found or list ends

If the element is not found, display “Element not found”

Stop

_______________________________________________________________________________________________

ALGORITHM 10: PRINT ODD NUMBERS BETWEEN 1 AND 10 USING WHILE LOOP

Start

Initialize a variable i with value 0

Check whether i is less than 10

Increment i by 1

Check if i is divisible by 2

If divisible by 2, skip the current iteration

Else display the value of i

Repeat steps 3 to 7 until the condition becomes false

Stop

_______________________________________________________________________________________________

CONCLUSION
Thus, we successfully studied and implemented conditional statements in Python to solve different decision-based problems. The experiment helped in understanding how logical conditions control program execution and how Python can be used to perform validations, comparisons, and practical computations effectively.
