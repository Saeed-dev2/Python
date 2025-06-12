# Python Tutorials

A comprehensive, beginner-to-intermediate Python tutorial series using Jupyter Notebook. This repository walks through Python fundamentals and transitions smoothly into data manipulation using the powerful **Pandas** library.

## 📚 Table of Contents

1. [Introduction](#introduction)
2. [Python Data Types](#python-data-types)
3. [Control Structures](#control-structures)
4. [Functions & Lambda Expressions](#functions--lambda-expressions)
5. [File Input/Output](#file-inputoutput)
6. [Pandas Library](#pandas-library)
   - Series
   - DataFrames
7. [Data Viewing & Manipulation](#data-viewing--manipulation)

---

## 📌 Introduction

Python is a high-level, interpreted programming language known for its readability, simplicity, and powerful community. It’s ideal for data analysis, web development, automation, and more.

- Open-source and cross-platform
- Beginner-friendly syntax
- Excellent for scientific computing and analytics

---

## 🔤 Python Data Types

### Variables
Dynamic typing allows variables to be declared without explicit types.

### Numeric Types
- `int`, `float`, `complex`
- Support for arithmetic and exponentiation

### Strings
- Immutable sequences of characters
- String slicing, formatting, and manipulation

### Lists
- Mutable ordered collections
- Supports mixed data types and slicing

### Dictionaries
- Key-value mappings with unique keys
- Supports dynamic insertion, deletion, and updates

### Tuples
- Immutable sequences
- Useful for fixed collections of items

### Sets
- Unordered collections of unique items
- Used for membership testing and set operations

---

## ⚖️ Comparison & Logical Operators

Includes:
- Relational: `==`, `!=`, `<`, `<=`, `>`, `>=`
- Logical: `and`, `or`, `not`, `in`, `not in`

---

## 🔁 Control Structures

### Conditional Statements
```python
if condition:
    # do something
elif another_condition:
    # do something else
else:
    # fallback
```
## 🔁 Loops
Python supports two main types of loops for iteration:

- **for** loop
- **while** loop

Features:
- Use of `range()` for generating sequences
- Demonstrates nested loops for advanced iteration patterns

---

## 🧠 Functions & Lambda Expressions

### User-Defined Functions
Functions in Python are defined using the `def` keyword and may include optional return values.

```python
def my_function(param):
    return param * 2
```

## 🧠 Lambda Functions

Anonymous, inline functions useful for short operations.

**Used with:**
- `map()`
- `filter()`
- `reduce()` (from `functools`)

**Example:**
```python
square = lambda x: x ** 2
print(square(4))  # Output: 16
```

# 🗂️ File Input/Output

## 📥 Keyboard Input

```python
input()  # For user interaction from keyboard
📄 File Handling Modes
"r" : Read

"w" : Write

"a" : Append

"r+" : Read and Write

"a+" : Append and Read

🔧 File Operations
read(), write(), close()

seek(), tell() – for file position management

os.rename(), os.remove() – for file renaming and deletion

🐼 Pandas Library
A powerful library for data analysis, built on top of NumPy.

📌 Series
One-dimensional labeled array

Supports slicing, indexing, vectorized operations

Can be created from:

dict

ndarray

scalar

📊 DataFrames
Two-dimensional labeled data structure

Can be created from:

dict of Series/lists

List of dicts

dict of tuples

Structured NumPy arrays

⚙️ Key Operations
Column/row selection, insertion, deletion

Arithmetic operations and label alignment

Transposing with .T

Sorting:

.sort_values()

.sort_index()

Boolean indexing and filtering

👁️ Data Viewing & Manipulation
.head() – View first 5 rows

.tail(n) – View last n rows

.describe() – Get summary statistics

.sort_values(by='column') – Sort by values

.sort_index() – Sort by index

🔍 Indexing
.loc[] – Label-based

.iloc[] – Integer position-based

Slicing with : notation

✅ Boolean Filtering
Using logical expressions

.isin() method

💻 How to Run
📥 Install Anaconda
👉 Download Anaconda

🚀 Launch Jupyter Notebook
Start via Anaconda Navigator
or

Run the following in terminal:


jupyter notebook
📂 Open the Notebook
Open Python-Tutorials.ipynb from the file browser.

▶️ Run Each Cell
Use Shift + Enter to execute each cell and follow along with the code and theory.

## 🧑‍💻 Author

**Muhammad Saeed**  
BSc Electrical Engineering    
Expert in Python, Embedded Systems, and AI Applications
