Python Day 7 🐍

📚 Topics Covered

This notebook focuses on Python Dictionaries, dictionary operations and methods, working with employee data, copying objects, and the join() method.

1. Dictionary

Dictionary declaration using {}

Dictionary creation using dict()

Key-value pair structure

Adding and modifying values

Retrieving values using keys

2. Dictionary Methods

The notebook demonstrates:

get() – safely retrieves a value for a key

keys() – returns dictionary keys

values() – returns dictionary values

items() – returns key-value pairs

update() – updates a dictionary

pop() – removes a specified item

popitem() – removes the last item

clear() – removes all items

dict.fromkeys() – creates a dictionary from a list of keys

3. Common Dictionary Operations

in

not in

==

!=

4. Employee Dictionary

An employee dataset is created with:

emp_id

emp_name

dept

age

emp_sal

The notebook demonstrates retrieving employee information by index and displaying employee details.

5. Employee Search Program

A practical program allows searching for an employee using:

Employee Name

Employee ID

Department

The program displays the employee's ID, name, department, age, and salary. If no matching employee is found, it displays an appropriate message.

6. Shallow Copy

The notebook demonstrates copy.copy() with nested lists. Changes to nested data in the shallow copy also affect the original nested data.

7. Deep Copy

The notebook demonstrates copy.deepcopy(). Changes to nested data in the deep copy do not affect the original object.

8. join()

The notebook demonstrates combining strings from a list using join().

Example:

l = ["abc", "xyz"]
"".join(l)

Output:

abcxyz

🧠 Key Learning

Dictionaries store data using key-value pairs.

Values can be added, modified, and retrieved using keys.

get() helps safely retrieve dictionary values.

keys(), values(), and items() access different parts of a dictionary.

pop(), popitem(), del, and clear() remove dictionary data.

update() modifies or adds dictionary data.

Shallow and deep copies behave differently with nested mutable objects.

join() combines sequence elements into a string.

📁 File

pythonDay7.ipynb — Jupyter Notebook containing the examples and practice programs.

🛠️ Requirements

Python 3

Jupyter Notebook / JupyterLab

▶️ How to Run

Open pythonDay7.ipynb in Jupyter Notebook or JupyterLab.

Run the cells sequentially.

Review the outputs.

Modify the examples and practice the concepts.

Day 7 of my Python learning journey 🚀
