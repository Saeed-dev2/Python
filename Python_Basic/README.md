
# 📘 Python Tutorials

A comprehensive, beginner-to-intermediate Python tutorial series using **Jupyter Notebook**. This repository walks through Python fundamentals and transitions smoothly into data manipulation using the powerful **Pandas** library.

---

## 📚 Table of Contents

- [📌 Introduction](#📌-introduction)
- [🔤 Python Data Types](#🔤-python-data-types)
- [⚖️ Comparison & Logical Operators](#⚖️-comparison--logical-operators)
- [🔁 Control Structures](#🔁-control-structures)
- [🧠 Functions & Lambda Expressions](#🧠-functions--lambda-expressions)
- [🗂️ File Input/Output](#🗂️-file-inputoutput)
- [🐼 Pandas Library](#🐼-pandas-library)
- [👁️ Data Viewing & Manipulation](#👁️-data-viewing--manipulation)
- [💻 How to Run](#💻-how-to-run)

---

## 📌 Introduction

Python is a high-level, interpreted programming language known for:

- Open-source and cross-platform support  
- Beginner-friendly syntax  
- Excellent capabilities for scientific computing and analytics

---

## 🔤 Python Data Types

- **Variables**  
  - Dynamic typing  
- **Numeric Types**: `int`, `float`, `complex`  
  - Arithmetic, exponentiation support  
- **Strings**  
  - Immutable, slicing, formatting  
- **Lists**  
  - Mutable, supports slicing and mixed types  
- **Dictionaries**  
  - Key-value pairs with dynamic updates  
- **Tuples**  
  - Immutable, fixed-length collections  
- **Sets**  
  - Unique items, used for membership testing and operations

---

## ⚖️ Comparison & Logical Operators

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

### Loops

- `for` loop  
- `while` loop  
- Use of `range()`  
- Nested loops for complex iteration

---

## 🧠 Functions & Lambda Expressions

### User-Defined Functions

```python
def my_function(param):
    return param * 2
```

### Lambda Functions

- Anonymous inline functions  
- Useful with: `map()`, `filter()`, `reduce()`  

Example:
```python
square = lambda x: x ** 2
print(square(4))  # Output: 16
```

---

## 🗂️ File Input/Output

### 📥 Keyboard Input
```python
input()  # For user interaction
```

### 📄 File Handling Modes

- `"r"` : Read  
- `"w"` : Write  
- `"a"` : Append  
- `"r+"` : Read and Write  
- `"a+"` : Append and Read  

### 🔧 File Operations

- `read()`, `write()`, `close()`  
- `seek()`, `tell()`  
- `os.rename()`, `os.remove()`

---

## 🐼 Pandas Library

A powerful data analysis library built on top of **NumPy**.

### 📌 Series

- 1D labeled arrays  
- Slicing, indexing, vectorized ops  
- Constructed from: `dict`, `ndarray`, scalar

### 📊 DataFrames

- 2D labeled data structures  
- Constructed from:  
  - `dict` of Series/lists  
  - List of dicts  
  - `dict` of tuples  
  - Structured NumPy arrays

### ⚙️ Key Operations

- Column/row manipulation  
- Arithmetic with label alignment  
- Transposing: `.T`  
- Sorting: `.sort_values()`, `.sort_index()`  
- Boolean indexing & filtering

---

## 👁️ Data Viewing & Manipulation

- `.head()` — First 5 rows  
- `.tail(n)` — Last n rows  
- `.describe()` — Summary statistics  
- `.sort_values(by='column')`  
- `.sort_index()`  

### 🔍 Indexing

- `.loc[]` — Label-based  
- `.iloc[]` — Integer-based  
- Slicing with `:`  
- Boolean filtering: `.isin()`

---

## 💻 How to Run

### 📥 Install Anaconda

👉 [Download Anaconda](https://www.anaconda.com/products/distribution)

### 🚀 Launch Jupyter Notebook

- Start via Anaconda Navigator  
- Or run in terminal:
```bash
jupyter notebook
```

### 📂 Open the Notebook

- Open `Python-Tutorials.ipynb` from the browser

### ▶️ Run Each Cell

- Use `Shift + Enter` to execute cells and follow along

---

Happy Learning! 🚀


## 🧑‍💻 Author

**Muhammad Saeed**  
BSc Electrical Engineering    
Expert in Python, Embedded Systems, and AI Applications
