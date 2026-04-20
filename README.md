# 🌍 Language Detection using Machine Learning & NLP

A Machine Learning project that automatically detects the **language of a given text** using Natural Language Processing (NLP) techniques. The model is trained on a multilingual dataset and achieves high accuracy in classifying text across multiple languages.

---

## 📊 Project Overview

This project focuses on building a **Language Detection System** that can identify the language of input text. It uses text vectorization and a probabilistic machine learning model to perform accurate predictions.

The system can be useful in:

* Chat applications
* Content filtering
* Multilingual platforms
* Search engines

---

## 📁 Dataset Description

* **File:** `https://github.com/fawwazkhan008/language-detection-ml/blob/main/language.csv`
* **Total Records:** 22,000
* **Languages Covered:** 22

### 🔤 Supported Languages

English, French, Spanish, German, Chinese, Japanese, Arabic, Hindi, Tamil, Turkish, Dutch, Romanian, Estonian, Swedish, Thai, Urdu, Persian, Indonesian, Korean, Latin, Portuguese, Pushto

✔ The dataset is **balanced** (1000 samples per language)

---

## ⚙️ Tech Stack

* **Python**
* **Pandas & NumPy** – Data handling
* **Scikit-learn** – Machine Learning
* **NLP Techniques** – Text preprocessing & vectorization

---

## 🧠 Model Details

* **Algorithm Used:** Multinomial Naive Bayes
* **Feature Extraction:** CountVectorizer
* **Train-Test Split:** 67% training / 33% testing

---

## 📊 Model Performance

* ✅ **Accuracy:** ~95.3%

The model performs well across multiple languages due to a balanced dataset and efficient text representation.

---

## 📂 Project Structure

```id="n1p2qs"
language-detection-ml/
│── language.csv
│── Machine Learning+NLP Project Language Detection.ipynb
│── ML+NLP Project Language Detection.pdf
│── README.md
```

---

## 📸 Project Preview

### 🔹 Model Accuracy

*Add screenshot of accuracy output here (model.score)*

### 🔹 Language Prediction

*Add screenshot of prediction example (user input → output)*

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/fawwazkhan008/language-detection-ml.git
   ```

2. Install required libraries:

   ```bash
   pip install pandas numpy scikit-learn
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Execute all cells and test with your own input

---

## 💡 Example Usage

```id="jyyvwd"
Input: "Bonjour tout le monde"
Output: French
```

```id="mjj08z"
Input: "Hello, how are you?"
Output: English
```

---

## 🔮 Future Improvements

* Use advanced NLP models (TF-IDF, Word2Vec, Deep Learning)
* Deploy as a web application
* Add real-time language detection API
* Improve performance for short text inputs

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 👤 Author

**Fawwaz Khan**
GitHub: https://github.com/fawwazkhan008

---

⭐ If you found this project useful, consider giving it a star!