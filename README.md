
# 🐍 Python Projects Repository

Welcome to the **Python Projects Repository**! This repository hosts multiple beginner-to-intermediate level Python-based projects with well-documented code and practical demonstrations. Explore two main projects included here:

---

## 📘 Project 1: Python Tutorials with Pandas

A comprehensive, beginner-to-intermediate Python tutorial series using **Jupyter Notebook**. This project introduces Python fundamentals and transitions smoothly into powerful data manipulation using the **Pandas** library.

### 📚 Table of Contents

- Introduction  
- Python Data Types  
- Control Structures  
- Functions & Lambda Expressions  
- File Input/Output  
- Pandas Library  
  - Series  
  - DataFrames  
  - Data Viewing & Manipulation  

### 📌 Introduction

Python is a high-level, interpreted programming language known for its readability, simplicity, and vibrant community. It’s ideal for:

- Data analysis  
- Web development  
- Automation  
- Scientific computing  

### 🔤 Python Data Types

- **Variables**: Dynamically typed  
- **Numeric Types**: `int`, `float`, `complex`  
- **Strings**: Immutable sequences  
- **Lists**: Mutable ordered collections  
- **Dictionaries**: Key-value mappings  
- **Tuples**: Immutable sequences  
- **Sets**: Unordered collections of unique items  

### ⚖️ Comparison & Logical Operators

- Relational: `==`, `!=`, `<`, `<=`, `>`, `>=`  
- Logical: `and`, `or`, `not`, `in`, `not in`

### 🔁 Control Structures

- **Conditional Statements**: `if`, `elif`, `else`  
- **Loops**: `for`, `while`, nested loops supported

### 🧠 Functions & Lambda Expressions

- Defined using `def`  
- Anonymous functions using `lambda`  
- Usage with `map()`, `filter()`, `reduce()`  

Example:
```python
square = lambda x: x ** 2
print(square(4))  # Output: 16
```

### 🗂️ File Input/Output

- `input()` for keyboard input  
- File modes: `"r"`, `"w"`, `"a"`, `"r+"`, `"a+"`  
- Operations: `read()`, `write()`, `close()`, `seek()`, `tell()`  
- File management: `os.rename()`, `os.remove()`  

### 🐼 Pandas Library

A high-performance library for data analysis and manipulation.

#### 📌 Series

- 1D labeled arrays  
- Supports slicing, indexing, vectorized operations  
- Constructed from `dict`, `ndarray`, or scalar  

#### 📊 DataFrames

- 2D labeled data structure  
- Constructed from lists of dicts, dict of Series, structured arrays, etc.  

#### ⚙️ Key Operations

- Column/row selection  
- Arithmetic operations  
- Transposing with `.T`  
- Sorting: `.sort_values()`, `.sort_index()`  
- Boolean indexing and filtering  

#### 👁️ Data Viewing & Manipulation

- `.head()`, `.tail(n)`, `.describe()`  
- Indexing with `.loc[]`, `.iloc[]`  
- Boolean filtering using `.isin()` and conditions  

### 💻 How to Run

1. 📥 **Install Anaconda**  
   👉 [Download Anaconda](https://www.anaconda.com/products/distribution)

2. 🚀 **Launch Jupyter Notebook**  
   - Start via Anaconda Navigator  
   - Or run in terminal:
     ```bash
     jupyter notebook
     ```

3. 📂 **Open the Notebook**  
   - Navigate to `Python-Tutorials.ipynb`

4. ▶️ **Run Cells**  
   - Use `Shift + Enter` to execute cells

---

## 📝 Project 2: Sentence Splitting using NLTK

A simple yet effective demonstration of using **NLTK (Natural Language Toolkit)** to split a paragraph into individual sentences.

### 🧪 Steps Overview

#### 📦 Step 1: Import the Library
```python
import nltk
```

#### 🔧 Step 2: Import Tokenizer
```python
from nltk.tokenize import sent_tokenize
```

#### 📝 Step 3: Define Your Text
```python
text = "All the great players and great people have one thing in common. They work even harder when no one is watching them."
```

#### ✂️ Step 4: Tokenize into Sentences
```python
sentences = sent_tokenize(text)
```

#### 📤 Step 5: Print the Output
```python
print(sentences)
```

> Output:
```python
['All the great players and great people have one thing in common.', 'They work even harder when no one is watching them.']
```

### 📚 Additional Information

- `sent_tokenize()` uses a **pre-trained Punkt tokenizer**.
- To use it for the first time:
```python
nltk.download('punkt')
```

### ✅ Summary

This program:
- Loads a paragraph of text.
- Splits the paragraph into individual sentences.
- Prints the result as a list of strings.

---

## 📂 Folder Structure

```
Python-Projects-Repo/
├── Python-Tutorials/
│   └── Python-Tutorials.ipynb
│   └── README.md
├── Sentence-Splitter-NLTK/
│   └── split_sentences.py
│   └── README.md
└── README.md  <-- [You are here]
```

Happy Coding! 🚀
