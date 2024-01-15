# NN_ICP-1

**1. ICP_1_1**
The provided Python code takes a word as input, creates a list of its characters, and then allows the user to input a number of strings to delete from the original word. After deletion, the code prints the reversed version of the remaining characters.

**Input:**

The user is prompted to enter a word.
The user is prompted to enter the number of strings they want to delete.
For each deletion, the user provides a string to be removed from the original word.

**Processing:**

The input word is converted into a list of characters (linst).
For each deletion, the specified string is removed from the list using the remove method.
The remaining characters in the list are joined into a single string (x).
The reversed version of the string is obtained using slicing (x[::-1]).
Output:

The reversed string is printed.
Example:

Enter word
python
Enter number of strings u want to delete
2
h
o
ntyp

The time complexity of the code is O(n^2) and the space complexity is O(n)


2.

Here's a brief documentation for the provided Python code:

Input:

The user is prompted to enter a sentence.
Processing:

The input sentence is split into a list of words using the split method.
For each word in the list, if the word is 'python', it is replaced with 'pythons'.
The modified list of words is then joined into a single string.
Output:

The modified sentence with the replacement of 'python' with 'pythons' is printed.
Example:

vbnet
Copy code
Input: I love python programming. Python is great.
Output: I love pythons programming. Pythons is great.
Time Complexity:

The time complexity of the code is O(n), where n is the total number of characters in the input sentence. The split method and the loop both have linear time complexity.
Space Complexity:

The space complexity is O(n), where n is the length of the input sentence. This is due to the storage of the split words in the list x. The space complexity could vary based on the length of the sentence and the number of words.

3.

Here's a brief documentation for the provided Python code:

Input:

The user is prompted to enter a floating-point number representing a score.
Processing:

The code checks the value of the input score against predefined ranges.
Based on the range in which the score falls, it prints the corresponding grade ('A', 'B', 'C', 'D', or 'F').
Output:

The grade corresponding to the input score is printed.
Example:

makefile
Copy code
Input: 87.5
Output: Grade B
Time Complexity:

The time complexity of the code is O(1). It involves a series of simple conditional checks, and the time it takes to execute does not depend on the size of the input.
Space Complexity:

The space complexity is O(1). The code uses a constant amount of memory regardless of the input size. There are no data structures or loops that would increase the space complexity based on input size.





