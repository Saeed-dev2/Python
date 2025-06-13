
# 📝 Splitting Text into Sentences using NLTK

This Python program demonstrates how to **split a paragraph into individual sentences** using the **Natural Language Toolkit (NLTK)**, a popular library for text processing and natural language tasks.

---

## 📦 Step 1: Import the NLTK Library

```python
import nltk
```
The `nltk` module is imported to access its text processing tools.

---

## 🔧 Step 2: Import the Sentence Tokenizer

```python
from nltk.tokenize import sent_tokenize
```
This line imports the `sent_tokenize` function, which is specifically designed to split a text into a list of sentences.

---

## 📝 Step 3: Define the Text

```python
text = "All the great players and great people have one thing in common. They work even harder when no one is watching them."
```
A sample paragraph is stored in a variable named `text`.

---

## ✂️ Step 4: Tokenize the Text into Sentences

```python
sentences = sent_tokenize(text)
```
This function breaks the paragraph into individual sentences using **pre-trained Punkt models**.

---

## 📤 Step 5: Output the Result

```python
print(sentences)
```
This line prints the list of sentences as the final output:

```
['All the great players and great people have one thing in common.', 'They work even harder when no one is watching them.']
```

---

## 📚 Additional Information

- `sent_tokenize` uses an unsupervised algorithm trained on large corpora to detect sentence boundaries.
- Make sure to run the following command once before using `sent_tokenize` to download the required models:

```python
nltk.download('punkt')
```

---

## ✅ Summary

This program:

1. Loads a paragraph of text.
2. Uses NLTK’s sentence tokenizer to split the text.
3. Prints out a list of cleanly separated sentences.

---
