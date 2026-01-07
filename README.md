# Fake News Detection Using NLP

This repository contains my week-wise learnings and code for the Fake News Detection project using Natural Language Processing (NLP).

---

## Week 1 — Python Basics

In Week 1, I focused on building the Python foundation required for NLP and Machine Learning.

### Topics Covered
- **Variables & Data Types**  
  Learned different data types in Python and how variables are used to store data.

- **Getting Input from Users**  
  Learned how to take input from users to make programs interactive.

- **Python Syntax**  
  Understood basic Python syntax and program structure.

- **Lists, Tuples, Sets**  
  Learned how lists, tuples, and sets work and their differences in flexibility and usage.

- **Type Casting**  
  Learned how to convert one data type into another.

- **Strings**  
  Worked with string slicing, modifying strings, format strings, escaping characters, and string methods like `capitalize()`, `upper()`, `lower()`, `index()` etc.

- **Operators**  
  Learned different types of operators used in Python.

- **Conditional Statements**  
  Used `if`, `else`, and `elif` to control program flow.

- **Dictionaries**  
  Learned dictionary syntax, storing data as key-value pairs, and operations like adding, changing, and removing elements.

- **Loops**  
  Practiced `while` loops and `for` loops, and understood the `range()` function. Compared Python loops with C++ loops.

- **Comments**  
  Learned how to write comments for code readability.

- **Functions**  
  Learned functions, default parameters, arguments, nested functions, recursion, and decorators.

- **Exception Handling**  
  Used `try` and `except` to handle runtime errors.

- **File Handling**  
  Learned reading from and writing to files.

- **Modules**  
  Learned about modules, similar to libraries in C++.

- **Classes and Objects**  
  Got a basic understanding of classes and objects (some topics not completed).

- **Practice Problems**  
  Solved Python problems from the CS101 course.

---

## Week 2 — Data Understanding & Text Preprocessing

In Week 2, I worked on understanding the dataset and preparing raw text data for NLP tasks.

### Dataset Understanding
- Checked what columns are present like `text` and `label`
- Understood that each row represents one news article
- Learned how labels indicate fake or real news

### Using Pandas for Dataset
- Loaded the dataset using `read_csv()`
- Viewed data using `head()`
- Checked dataset shape and column names
- Checked fake and real news count
- Checked missing values in the dataset
- Used only basic pandas required for EDA

### Text Preprocessing
- Converted text to lowercase to maintain consistency
- Removed punctuation and special characters to reduce noise
- Tokenized text into individual words
- Removed stopwords that do not add meaning
- Applied lemmatization to convert words to base form

### Libraries Used
- **pandas** – for loading and exploring the dataset  
- **nltk** – for tokenization, stopword removal, and lemmatization  
- **re** – for cleaning text using regular expressions  

---

## Week 3 — Feature Extraction

In Week 3, I learned how to convert cleaned text into numerical features that can be used by machine learning models.

### Understanding Feature Extraction
- Learned why machine learning models cannot work directly on raw text
- Understood that text must be converted into numerical form before training models

### Bag of Words (BoW)
- Learned the concept of Bag of Words representation
- Understood how text is converted into word frequency vectors
- Learned how vocabulary is created from the dataset

### TF-IDF (Term Frequency – Inverse Document Frequency)
- Learned how TF-IDF improves over Bag of Words
- Understood term frequency and inverse document frequency
- Learned how important words get higher weight and common words get lower weight
- Applied TF-IDF to convert cleaned text into numerical features

### Using Sklearn for Feature Extraction
- Used `TfidfVectorizer` from sklearn
- Learned how text data is transformed into feature matrices
- Understood how these features are passed to machine learning models

### Mentor Code Notebook
- Went through the Week 3 code shared by the mentor
- Understood how feature extraction is applied after text preprocessing
- Learned how this step connects preprocessing with model training

### What I Learned in Week 3
- How text is converted into numbers using feature extraction
- Difference between Bag of Words and TF-IDF
- Why TF-IDF is commonly used in text classification tasks
- How feature extraction is a key step before training ML models
