# 📧 Email / SMS Spam Detection using Machine Learning

## 📌 Overview
This project focuses on building a **machine learning–based spam detection system** that classifies messages as **Spam** or **Not Spam (Ham)** using **Natural Language Processing (NLP)** techniques.

The goal is to demonstrate an **end-to-end ML workflow**, including data preprocessing, feature extraction, model training, and evaluation.

---

## 🚀 Features
- Text preprocessing (cleaning, tokenization, stopword removal)
- Feature extraction using **TF-IDF Vectorization**
- Classification using **Naive Bayes / Logistic Regression**
- Model evaluation using accuracy, precision, recall, and confusion matrix

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, NLTK  
- **Visualization:** Matplotlib, Seaborn  
- **ML Techniques:** NLP, Classification, TF-IDF  

---


---

## 📊 Dataset
The dataset contains labeled email/SMS messages:
- **Label:** Spam / Ham  
- **Message:** Text content of the message  

---

## ⚙️ How It Works
1. Load and explore the dataset  
2. Clean and preprocess text data  
3. Convert text into numerical features using TF-IDF  
4. Train a classification model  
5. Evaluate model performance  

---

## 📈 Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## ▶️ How to Run the Project
```bash
# Clone the repository
git clone https://github.com/Praveen-kumar1Singh/email-spam-detection-ml.git

# Navigate to the project folder
cd email-spam-detection-ml

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/spam_detection.ipynb

