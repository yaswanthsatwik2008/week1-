## week1-
Python Basics
-Variables& Data Types
-Getting Input from Users
  learning syntax
-Lists,Tuples,Sets
  their differences in flexibilities
-Type Casting
  changing one type to another
-Strings
  slicing,modifying,adding
  format strings(better)
  escaping characters in a string
  string methods(capitalize(),upper(),lower(),index() etc.,)
-operators
-if..else
  elif
-dictionaries
  syntax
  stores data in key:value pairs
  adding,changing,removing etc.,
-while loops
  similar to c++
-for loops
  similar to c++ but syntax
  range function
-Comments
-functions
  default parameters
  arguments
  function inside functions(can be recursions)
  decoraters
-try except
-reading and writing files
-modules
  similar to libraries in c++
-classes and objects
  just basics (some topics not completed)
-Also done some problems in python language which are in cs101 course
## week2 — Data Understanding & Text Preprocessing

### Dataset Understanding
- Checked what columns are present like text and label  
- Understood that each row represents one news article  
- Learned how labels indicate fake or real news  

### Using Pandas for Dataset
- Loaded the dataset using read_csv()  
- Viewed data using head()  
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
- pandas – for loading and exploring the dataset  
- nltk – for tokenization, stopword removal, and lemmatization  
- re – for cleaning text using regular expressions
  ## week3 — Feature Extraction

### Understanding Feature Extraction
- Learned why machine learning models cannot work directly on raw text  
- Understood that text needs to be converted into numerical form before training models  

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
- Used TfidfVectorizer from sklearn  
- Learned how text data is transformed into feature matrices  
- Understood how these features are passed to machine learning models  

### Mentor Code Notebook
- Went through the week 3 code shared by the mentor  
- Understood how feature extraction is applied after text preprocessing  
- Learned how this step connects preprocessing with model training  

### What I Learned in Week 3
- How text is converted into numbers using feature extraction  
- Difference between Bag of Words and TF-IDF  
- Why TF-IDF is commonly used in text classification tasks  
- How feature extraction is a key step before training ML models  


