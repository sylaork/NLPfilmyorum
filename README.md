# 🎬 Sentiment Analysis on IMDB Movie Reviews

This project is an NLP-based application that analyzes the sentiment of movie reviews from the IMDB dataset. The main goal is to help users decide whether a movie is worth watching based on review sentiment—positive or negative.

## 📌 Project Overview

- 📥 Users enter a movie review as input.
- 🤖 The model predicts whether the sentiment is positive or negative.
- 🎯 The output helps users make better viewing decisions.

---

## 📚 Dataset

- **IMDB Movie Reviews Dataset (50,000 samples)**
- Each review is labeled as either **positive** or **negative**.
- Balanced dataset: 25,000 reviews for each class.
- Source: [Kaggle - IMDB Dataset](https://www.kaggle.com/datasets)

---

## 🧹 Data Preprocessing Steps

- Convert all text to lowercase
- Remove HTML tags (e.g., `<br>`)
- Eliminate numbers and URLs
- Remove punctuation
- Normalize white spaces

---

## 🧠 Model & Methodology

### ✨ TF-IDF + Logistic Regression

- **TF-IDF**: Highlights meaningful words and reduces the impact of frequently occurring but less informative terms.
- **Logistic Regression**: A simple yet effective classifier for binary sentiment prediction.

### Alternative: Naive Bayes
- While fast and easy to implement, it assumes word independence, which may miss contextual nuances in sentiment analysis.

---

## 🖥️ Application Interface

The user interface was built with **Streamlit**, inspired by a prototype created on Hugging Face.

### Features:
- Themed visuals
- Text input for user reviews
- A "Predict" button
- Accuracy display
- Output sentiment: Positive or Negative
- Recommendation suggestion based on the prediction

---

## 📊 Results

- ✅ **Model Accuracy:** 88.66%
- ☑️ High recall for positive sentiment
- ☑️ High precision for negative sentiment
- 🔁 Balanced F1 scores: The model performs well on both classes

---

## ⚙️ Challenges Faced

- Finding a balanced and clean dataset
- Streamlit UI integration
- Improving model performance

---

## 🔮 Future Work

- Implementing a rating prediction system (e.g., 1–10 scale)
- Predicting the actual IMDB score from review content
- Incorporating advanced NLP techniques to improve accuracy

---

## 📌 Live Demo

📺 https://huggingface.co/spaces/sylaork/filmyorum


---

## 👩‍💻 About the Developer

**Sıla Orak**  
Project for Natural Language Processing course  

---

