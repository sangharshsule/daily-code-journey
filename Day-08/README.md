Python Day 8 🐍

📚 Topics Covered

This notebook focuses on Python Loops, especially for loops, range(), indexing, list modification, counting, and enumerate().

1. Loops

Introduction to loops and how they are used to repeat tasks.

2. Simple for Loop

The notebook demonstrates iterating through a list using a temporary variable.

Example:

for task in tasks:
    print(task)

It also demonstrates iterating through a list of fruits and converting each fruit name to uppercase using .upper().

3. Understanding range()

The notebook covers the syntax:

range(start, stop, step)

Key points:

Generates a sequence of numbers.

Commonly used with loops.

The stop value is excluded.

If one argument is provided, it is treated as the stop value.

Useful for controlled iteration, repeating tasks, and indexing.

4. range() with Conditions

Examples include:

Printing numbers from 0 to 10

Checking whether numbers are even or odd using %

Counting odd numbers between 1 and 30

5. Looping Through Lists Using Indexes

The notebook demonstrates:

Finding the length of a list using len()

Using range() with list indexes

Accessing list elements using tasks[i]

6. Modifying Lists During Iteration

The notebook demonstrates list operations such as:

append() – adding elements

pop() – removing elements by index

remove() – removing specific values

These operations are combined with loops to manipulate and display list data.

7. Counting Vowels

A practical program counts vowels in a user-entered sentence.

The program:

Defines vowels as aeiouAEIOU

Takes a sentence as input

Iterates through each character

Checks whether the character is a vowel

Counts the total number of vowels

8. Understanding enumerate()

The notebook introduces:

enumerate(iterable, start=0)

It is used to access both the index and value while iterating through a sequence.

Example:

for index, value in enumerate(tasks, start=0):
    print(index, value)

It also demonstrates starting enumeration from 1 when displaying names.

🧠 Key Learning

for loops are used to iterate through sequences.

range() generates a sequence of numbers for controlled iteration.

The stop value in range() is excluded.

len() can be combined with range() to iterate through list indexes.

% can be used to identify even and odd numbers.

Lists can be modified using append(), pop(), and remove().

Loops can be used for practical tasks such as counting vowels.

enumerate() provides both index and value during iteration.

📁 File

pythonDay8(1).ipynb — Jupyter Notebook containing the loop examples and practice programs.

🛠️ Requirements

Python 3

Jupyter Notebook / JupyterLab

▶️ How to Run

Open the notebook in Jupyter Notebook or JupyterLab.

Run the cells sequentially.

Review the outputs.

Modify the examples and practice the loop concepts.

Day 8 of my Python learning journey 🚀
