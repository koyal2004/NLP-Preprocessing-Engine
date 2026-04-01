# 🧠 NLP Preprocessing Engine (Advanced)

## 📌 Internship Task

**Data Science Internship – February 2026**
**Task 1: Build a Robust NLP Preprocessing Engine**

---

## 🚀 Project Overview

In real-world Natural Language Processing (NLP) systems, raw text data is often noisy, inconsistent, and unstructured.
This project focuses on building a **modular, scalable, and reusable NLP preprocessing pipeline** to clean and transform such data into meaningful tokens for machine learning models.

---

## 🎯 Objectives

* Design a robust NLP preprocessing pipeline
* Handle noisy real-world text (emojis, URLs, repeated characters)
* Apply text normalization techniques
* Perform token-level statistical analysis
* Write clean, maintainable Python code

---

## ⚙️ Features Implemented

### ✅ Text Preprocessing

* Convert text to lowercase
* Remove URLs and email patterns
* Remove numbers
* Remove special characters and emojis
* Handle repeated characters (e.g., "soooo" → "soo")
* Remove extra spaces
* Tokenization
* Remove short tokens (≤2 length) with exceptions (`no`, `not`)

---

### ✅ Stress Testing

Tested on diverse real-world inputs including:

* Emojis 😍
* Numbers 🔢
* URLs 🌐
* Slang 💬
* Repeated characters 🔁
* Mixed case text 🔠

---

### ✅ Token Analytics

For each sentence:

* Total number of tokens
* Number of unique tokens
* Average token length

---

### ✅ Frequency Analysis

* Top 10 most frequent words
* Top 5 least frequent words
  (using `collections.Counter`)

---

### ✅ Full Pipeline Function

```python
def full_pipeline(text_list):
    return {
        "tokens": [...],
        "clean_sentences": [...]
    }
```

---

### ✅ Error Handling

Handles edge cases like:

* Empty strings
* Only emojis
* Only numbers

---

## 🧪 Sample Input

```python
"I absolutely looooved this product 😍😍"
```

## 🧾 Output

* Tokens: `['absolutely', 'looved', 'this', 'product']`
* Cleaned Sentence: `"absolutely looved this product"`

---

## 🛠️ Technologies Used

* Python 🐍
* Regular Expressions (`re`)
* NumPy
* Collections (`Counter`)
* Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```
NLP-Preprocessing-Engine/
│
├── NLP_Preprocessing.ipynb
├── README.md
```

---

## 🔗 How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Run all cells sequentially
3. View outputs for preprocessing, analytics, and testing

---

## 📊 Key Insights

* High-noise sentences were effectively cleaned
* Meaningful tokens were preserved after preprocessing
* Pipeline is reusable for real-world NLP tasks

---

## 📌 Submission Details

* Notebook uploaded in `.ipynb` format
* GitHub repository link submitted via Google Form

---

## 🙌 Author

**Koyal Mandal**
Data Science Student

---

## ⭐ Acknowledgment

This project was completed as part of the **Data Science Internship – February 2026 Assignment**.
