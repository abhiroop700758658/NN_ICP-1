# NN_ICP-1

**Code Execution Link** : https://drive.google.com/file/d/1tpX7kWAPI6CTGpqVOXiSDYHStIGDk1u_/view?usp=sharing

**1. ICP-1_1**
The provided Python code takes a word as input, creates a list of its characters, and then allows the user to input a number of strings to delete from the original word. After deletion, the code prints the reversed version of the remaining characters.

**Input:**

The user is prompted to enter a word.
The user is prompted to enter the number of strings they want to delete.
For each deletion, the user provides a string to be removed from the original word.

**Process:**

The input word is converted into a list of characters (linst).
For each deletion, the specified string is removed from the list using the remove method.
The remaining characters in the list are joined into a single string (x).
The reversed version of the string is obtained using slicing (x[::-1]).
Output:

The reversed string is printed.
**Example:**
Enter word
python
Enter number of strings u want to delete
2
h
o
ntyp

The time complexity of the code is O(n^2) and the space complexity is O(n)

**1.1 ICP-1_1.1**
This code is used to execute arithmetic operators
The user is prompted to enter two integer numbers (n1 and n2).

The code performs basic arithmetic operations on the input numbers.
Addition: n1 + n2
Subtraction: n1 - n2
Multiplication: n1 * n2
Division: n1 / n2
Modular Division (Remainder): n1 % n2

The results of these operations are printed.

The results of the arithmetic operations (addition, subtraction, multiplication, division, and modular division) are printed.

**Example:**
**Input:**
9
7

**Output:**
addition: 16
subtraction: 2
multiplication: 63
division: 1.28571
modular division: 1

The time complexity of the code is O(1) and the space complexity is O(1)

**2. ICP-1_2**
This code is used to modify or replace a word in a sentence.

**Input:**

The user is prompted to enter a sentence.

**Process:**

The input sentence is split into a list of words using the split method.
For each word in the list, if the word is 'python', it is replaced with 'pythons'.
The modified list of words is then joined into a single string.

**Output:**

The modified sentence with the replacement of 'python' with 'pythons' is printed

**Example:**

**Input:** 
I love playing with python
**Output:**
I love playing with pythons

The time complexity of the code is O(n) and the space complexity is O(n)

**3. ICP-1_2**
This code is used for calculating the grade for given marks for a subject or course.

**Input:**

The user is prompted to enter a floating-point number representing a score.

**Process:**

The code checks the value of the input score against predefined ranges.
Based on the range in which the score falls, it prints the corresponding grade ('A', 'B', 'C', 'D', or 'F').

**Output:**
The grade corresponding to the input score is printed.

**Example:**
**Input:**
87.5
**Output:**
Grade B

The time complexity of the code is O(1) and the space complexity is O(1)





