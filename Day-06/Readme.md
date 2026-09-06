Python Day 6 🐍

📚 Topics Covered

This notebook focuses on Python Tuples and Sets, including their declaration, manipulation, indexing, and common operations.

1. Tuple Declaration

Creating tuples with different data types

Checking the type of a tuple

2. Adding Elements to a Tuple

Three approaches are demonstrated:

Tuple concatenation using +

Converting a tuple to a list, adding an element, and converting it back

Modifying a mutable list stored inside a tuple

3. Tuple Packing and Unpacking

Packing: storing multiple values in a single tuple

Unpacking: assigning tuple values to individual variables

4. Tuple Indexing and Methods

Accessing tuple elements using indexes

count() – counts occurrences of a value

index() – finds the first index of a value

Demonstration of tuple immutability using item assignment

5. Set Declaration

Creating a set

Creating an empty set using set()

Difference between an empty set and an empty dictionary

Creating a set from a list

Understanding that sets do not support indexing

6. Set Methods

The notebook demonstrates:

add() – adds one element

update() – adds multiple elements

discard() – removes an element without raising an error if it is absent

remove() – removes an element and raises an error if it is absent

pop() – removes an element from the set

clear() – removes all elements

7. Set Operations

union() – combines elements from two sets

intersection() – returns common elements

difference() – returns elements present in the first set but not the second

symmetric_difference() – returns elements that are present in either set, but not both

8. Built-in Functions with Sets

len() – number of elements

max() – maximum element

min() – minimum element

sum() – sum of elements

🧠 Key Learning

Tuples are immutable, so their elements cannot normally be changed after creation.

A tuple can contain mutable objects such as lists, and those objects can still be modified.

Sets store unique elements and do not support indexing.

discard() and remove() behave differently when the requested element is absent.

Set operations are useful for comparing and combining collections.

📁 File

pythonDay6.ipynb — Jupyter Notebook containing the examples and practice code.

🛠️ Requirements

Python 3

Jupyter Notebook / JupyterLab

▶️ How to Run

Open pythonDay6.ipynb in Jupyter Notebook or JupyterLab.

Run the cells sequentially.

Review the outputs and experiment by modifying the examples.

Day 6 of my Python learning journey 🚀
