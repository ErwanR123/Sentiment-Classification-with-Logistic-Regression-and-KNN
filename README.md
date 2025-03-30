# Sentiment Analysis: Logistic Regression vs KNN

## 📌 Project Overview

This project focuses on building and comparing two machine learning models – **Logistic Regression** and **K-Nearest Neighbors (KNN)** – for binary sentiment analysis. After evaluating their performance, Logistic Regression was selected as the final model due to its higher accuracy and consistency.

A simple user interface is also provided, allowing users to input custom text and receive the predicted probability that the sentiment is positive or negative.

The dataset used in this project is the **IMDB Dataset of 50K Movie Reviews**, available on Kaggle and labeled for binary sentiment classification.

## 🧠 Key Features

- Preprocessing and vectorization of textual data
- Model training and evaluation using Logistic Regression and KNN
- Performance comparison using metrics such as Accuracy, F1-score, and Confusion Matrix
- Interactive sentiment prediction using the final model

## 🔍 Model Evaluation

After training both models, Logistic Regression showed significantly better performance:
- Higher accuracy and F1-score
- Fewer misclassifications in the confusion matrix
- More balanced predictions across both sentiment classes

Therefore, Logistic Regression was selected as the final model for deployment.

## 🛠️ Tech Stack

- Python 3.x
- Scikit-learn
- Pandas & NumPy
- Matplotlib (for optional visualizations)
- [Optional] Tkinter or Streamlit for the interface


📈 Future Improvements
Integrate more advanced models (e.g., SVM, Random Forest, BERT)

Improve the interface with a web app using Streamlit

Expand the dataset for better generalization

Feel free to contribute, open issues, or fork the project!

