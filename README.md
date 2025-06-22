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

## 🏷️ Project 3:  Label Encoding with Python

This project demonstrates how to perform **label encoding** using Python in a Jupyter Notebook. Label encoding is a data preprocessing technique used in machine learning to convert categorical labels into numeric form so that algorithms can work effectively with the data.

---

## 📁 File Description

- `Label_Encoding.ipynb`: Jupyter notebook that contains Python code for performing label encoding on a sample dataset using `pandas`.

---

## 📚 Objectives

- Understand the concept of label encoding
- Create a sample dataset with categorical features
- Apply label encoding using different methods
- Analyze the effects of encoding on the dataset

---

## 🔧 Technologies and Libraries Used

- Python 3
- pandas
- numpy
- Jupyter Notebook

---

## 🚀 Workflow Overview

### 1. Import Libraries

The notebook starts by importing necessary libraries:
```python
import pandas as pd
import numpy as np
```

### 2. Create a Dataset

A sample dataset is created with one or more categorical columns that require encoding. These columns represent categories like `Country`, `Color`, `Gender`, etc.

### 3. Perform Label Encoding

Label encoding is applied using:
- `pandas.factorize()`
- `pandas.Categorical().codes`

Example:
```python
df['encoded'] = pd.factorize(df['category_column'])[0]
```

### 4. Compare Encoded Results

The encoded results are compared with the original data to understand the transformation.

---

## 📈 Use Cases of Label Encoding

- Preparing categorical data for machine learning models
- Converting textual class labels to integers
- Encoding target labels in supervised learning

---

## ✅ Best Practices

- Ensure that the categorical variables are ordinal if using Label Encoding.
- For nominal (non-ordered) categories, consider using **One-Hot Encoding** to prevent unintended ordinal relationships.

---

## 📌 Note

Label Encoding assigns each unique category value an integer, which can introduce unintended order relationships. Be cautious when using it with nominal data.

---



## 📂 Folder Structure
```
Python-Projects-Repo/
├── Python-Basic/
│   └── Python_Assignment_1.ipynb
│   └── README.md
├── Python_NLP/
│   └── Python_NLP.ipynb
│   └── README.md
├── Label-Encoding-Tutorial/
│   └── Label_Encoding.ipynb
│   └── README.md
└── README.md  <-- [You are here]
```


## 🧑‍💻 Author

**Muhammad Saeed**  
BSc Electrical Engineering    
Expert in Python, Embedded Systems, and AI Applications

Happy Coding! 🚀
