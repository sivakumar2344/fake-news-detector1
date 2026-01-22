# **Fake News Detection using Machine Learning**

**An AI-based system that detects whether a news article is Fake or Real using Machine Learning and Natural Language Processing (NLP).**

---

## **Features**
- Uses real Kaggle datasets (Fake.csv and True.csv)
- Text preprocessing and cleaning
- TF-IDF vectorization
- Logistic Regression classifier
- High accuracy (~99%)
- Streamlit web application for real-time prediction

---

## **Technologies Used**
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  

---

## **Dataset**
The dataset consists of:
- Fake.csv – Fake news articles  
- True.csv – Real news articles  

Source: Kaggle Fake News Dataset

---

## **How It Works**
1. Load and merge fake and real news datasets  
2. Preprocess text data  
3. Convert text into numerical features using TF-IDF  
4. Train Logistic Regression model  
5. Predict whether the given news is Fake or Real  

---

## **How to Run the Project**

### **Step 1: Install Dependencies**
```bash
pip install -r requirements.txt
