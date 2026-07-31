# 📝 NLP Text Preprocessing

## 📌 Project Description

This project demonstrates basic **Natural Language Processing (NLP)** techniques using Python. It reads raw text from a file, analyzes the text, identifies different patterns, and removes unwanted elements through text preprocessing.

## 🎯 Objective

The main objective of this project is to preprocess raw text by:

* Reading text from a file
* Displaying the original raw text
* Finding basic text information
* Converting text into lowercase
* Detecting URLs
* Extracting hashtags and mentions
* Splitting text into words
* Removing HTML tags
* Removing URLs
* Removing email addresses
* Removing hashtags and mentions
* Removing numbers
* Removing special characters
* Removing extra spaces
* Saving the cleaned text into an output file

## 🛠️ Technologies Used

* **Python**
* **Regular Expressions (re)**
* **NLTK**
* **File Handling**

## 📂 Project Structure

```text
NLP-TEXT-PREPROCESSING/
│
├── preprossing.py
├── raw.txt
├── README.md
│
└── output/
    └── clean.txt
```

## ⚙️ Features

### 1. Read Raw Text

The program reads the original text from the `raw.txt` file using Python file handling.

### 2. Display Original Text

The raw text is displayed before performing any preprocessing operations.

### 3. Text Information

The program calculates:

* Number of characters
* Number of words
* Number of lines

### 4. Lowercase Conversion

All text is converted into lowercase to maintain consistency during text processing.

### 5. URL Detection

The `re.search()` function is used to check whether a URL is present in the text.

### 6. Pattern Extraction

The `re.findall()` function is used to extract:

* URLs
* Hashtags
* Mentions
* Email addresses
* Numbers

### 7. Text Splitting

The `re.split()` function is used to split the text into individual words.

### 8. HTML Tag Removal

HTML tags such as `<div>` and other markup elements are removed from the raw text.

### 9. URL Removal

Website links and URLs are removed from the text.

### 10. Email Removal

Email addresses are removed to produce cleaner text.

### 11. Hashtag and Mention Removal

Social media hashtags and mentions are removed using regular expressions.

### 12. Number Removal

Numerical values are removed from the text.

### 13. Special Character Removal

Special characters and unnecessary symbols are removed.

### 14. Extra Space Removal

Multiple spaces are replaced with a single space.

### 15. Save Cleaned Text

The final cleaned text is saved in:

```text
output/clean.txt
```

## 🔄 Text Preprocessing Flow

```text
Raw Text
   ↓
Read Text File
   ↓
Display Text Information
   ↓
Convert to Lowercase
   ↓
Detect URLs
   ↓
Extract Patterns
   ↓
Split Text
   ↓
Remove HTML Tags
   ↓
Remove URLs
   ↓
Remove Emails
   ↓
Remove Hashtags & Mentions
   ↓
Remove Numbers
   ↓
Remove Special Characters
   ↓
Remove Extra Spaces
   ↓
Clean Text
   ↓
Save clean.txt
```

## 💻 How to Run

### Step 1: Install NLTK

```bash
pip install nltk
```

### Step 2: Prepare Files

Keep `raw.txt` and `preprossing.py` in the same folder.

### Step 3: Run the Python Program

```bash
python preprossing.py
```

### Step 4: Check Output

After execution, the cleaned text will be stored in:

```text
output/clean.txt
```

## 📤 Sample Output

```text
========== ORIGINAL RAW TEXT ==========

Hello! My name is Yuvahri...

========== TEXT INFORMATION ==========

Number of Characters : ...
Number of Words      : ...
Number of Lines      : ...

========== LOWERCASE TEXT ==========

hello! my name is yuvahri...

========== CLEANED DATA ==========

hello my name is yuvahri and i love exploring new technology
```

## ✅ Advantages

* Simple and easy to understand
* Removes unwanted text elements
* Uses regular expressions effectively
* Helps prepare text for further NLP tasks
* Automatically saves the cleaned data
* Can be applied to different raw text files

## ⚠️ Limitations

* Does not perform stemming
* Does not perform lemmatization
* Does not remove stopwords
* Does not perform tokenization using advanced NLP methods
* Basic regular expressions may not handle every type of text

## 🔮 Future Enhancements

The project can be improved by adding:

* Tokenization
* Stopword removal
* Stemming
* Lemmatization
* Part-of-Speech tagging
* Sentiment analysis
* Named Entity Recognition
* Text classification

## 🏁 Conclusion

This project demonstrates the basic process of **NLP text preprocessing using Python**. It shows how raw text can be analyzed and cleaned by removing unwanted elements such as URLs, emails, hashtags, mentions, numbers, HTML tags, and special characters. The cleaned text can then be used for further NLP tasks such as sentiment analysis, classification, and machine learning. Overall, text preprocessing is an important step in converting raw text into useful and meaningful data.
