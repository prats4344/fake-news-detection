# 📰 Fake News Detection Using Machine Learning

A machine learning model that classifies news articles as **Fake** or **Real** using Natural Language Processing (NLP) and classic ML techniques. The model has been trained and tested using real-world news data from Kaggle, and can even be manually tested with your own headlines!

---

## 🚀 Project Features

- ✅ Preprocessed real & fake news data
- ✅ Feature extraction using **TF-IDF**
- ✅ Multiple ML models trained:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting Classifier
- ✅ Built-in `manual_testing()` function for real-time testing

---

📁 Dataset Source
Fake and Real News Dataset - Kaggle

---

📊 Model Performance
Achieved ~97% accuracy across multiple classifiers

Evaluated using classification reports and confusion matrices

Handles real-sounding and absurd headlines to detect fakes

---
🧰 Tech Stack
Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Notebook: Google Colab

---

## 💡 Manual Testing Examples

Test the model with your own headlines!

```python
manual_testing("Aliens spotted playing cricket in Delhi.")

# Output:
# LR Prediction: Fake News
# DT Prediction: Fake News
# GBC Prediction: Fake News
# RFC Prediction: Fake News

