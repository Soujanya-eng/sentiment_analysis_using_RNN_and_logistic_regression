# Sentiment Analysis using RNN and TF-IDF with Logistic Regression

## Project Overview

This project focuses on Sentiment Analysis of IMDb movie reviews using two different approaches:

- Recurrent Neural Network (RNN)
- TF-IDF with Logistic Regression

The objective is to classify movie reviews as **Positive** or **Negative** and compare the performance of Machine Learning and Deep Learning models.

---

## Dataset

- Dataset: IMDb Movie Reviews Dataset
- Original Size: 50,000 Reviews
- Used for Training: 4,000 Reviews
- Classes:
  - Positive Reviews
  - Negative Reviews

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Google Colab

---

## Data Preprocessing

The following preprocessing steps were applied:

- HTML Tag Removal
- Lowercase Conversion
- Special Character Removal
- Stopword Removal
- Stemming using PorterStemmer

---

## Model 1: RNN (Recurrent Neural Network)

### Architecture

- Embedding Layer
- LMST Layer
- Dense Output Layer

### Results

- Lower Accuracy
- Overfitting observed during training

### Challenges

- Limited Dataset Size
- High Computational Cost
- Overfitting

---
## Model 2: TF-IDF + Logistic Regression

### Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency)

### Classifier

Logistic Regression

### Results

| Metric | Value |
|----------|----------|
| Accuracy | 86.75% |

### Advantages

- Fast Training
- Less Computational Cost
- Good Performance on Small Datasets
- Easy to Interpret

---

## 📊 Model Comparison

| Model | Accuracy |
|---------|---------|
| TF-IDF + Logistic Regression | 86.75% |
| RNN | ~73% |

### Observation

TF-IDF with Logistic Regression outperformed the RNN model on the selected subset of 4,000 IMDb reviews. The RNN model suffered from overfitting and lower generalization performance.

---

## ✅ Conclusion

This project implemented Sentiment Analysis using RNN and TF-IDF with Logistic Regression on 4,000 IMDb movie reviews. Experimental results showed that Logistic Regression achieved **86.75% accuracy** and outperformed the RNN model, which experienced overfitting and lower validation accuracy.

---

## 🚀 Future Enhancements

- Use larger datasets
- Implement LSTM 
- Hyperparameter Tuning
- Use Pretrained Word Embeddings
- Implementing more efficient Sentiment Analysis

---

## 👨‍💻 Author

**Soujanya Sharanagouda Ankalagi**

AI/ML Project – Sentiment Analysis using NLP and Deep Learning
