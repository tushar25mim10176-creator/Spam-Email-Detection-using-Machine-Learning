# 📄 Spam Email Detection using Machine Learning

## 👋 Introduction
This project is a simple and beginner-friendly implementation of a Spam Email Detection system using Machine Learning. The main idea is to teach how a computer can learn to differentiate between spam and normal emails based on their content.

In real life, email services like Gmail automatically filter spam messages. This project shows a basic version of how that works.

---

## 🎯 Objective
The objective of this project is:
- To understand basic concepts of Artificial Intelligence and Machine Learning
- To build a simple model that can classify emails
- To learn how text data is processed in machine learning

---

## 🧠 Concepts Used
This project is based on the following concepts:
- Machine Learning
- Text Classification
- Naive Bayes Algorithm
- Data Preprocessing
- Count Vectorization

---

## ⚙️ Tools & Technologies
- Python
- Scikit-learn (sklearn library)

---

## 🔄 How the Project Works

Step 1: A small dataset of emails is created manually  
Step 2: Each email is labeled as Spam (1) or Not Spam (0)  
Step 3: The text is converted into numbers using CountVectorizer  
Step 4: A Naive Bayes model is trained on this data  
Step 5: The model is tested on new email inputs  
Step 6: The model predicts whether the email is spam or not  

---

## 💻 How to Run the Project

### 1. Install Required Library
pip install scikit-learn

### 2. Run the Python Code
python spam_detection.py

---

## 📊 Example

### Input:
"Win a free lottery"  
"Let's meet for lunch"  

### Output:
Win a free lottery --> Not Spam  
Let's meet for lunch --> Spam  

---

## ⚠️ Important Note
Since this project uses a very small dataset, the accuracy may not be perfect. Machine learning models perform better with larger datasets.

---

## 🚀 Future Improvements
- Use a larger dataset
- Improve model accuracy
- Add graphical interface (GUI)
- Include accuracy score and evaluation metrics

---

## 📌 Conclusion
This project helps in understanding how machine learning can be applied to solve real-world problems like spam detection. It is simple, easy to understand, and a good starting point for beginners.

---

## 👨‍💻 Author
Tushar Sen
