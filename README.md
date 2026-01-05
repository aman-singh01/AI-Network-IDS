# AI-Based-Network-IDS_ML-DL

AI-Based-Network-IDS_ML-DL is a project focused on building an intelligent **Network Intrusion Detection System (NIDS)** using **Machine Learning (ML)** and **Deep Learning (DL)** techniques. The goal of this project is to detect malicious network activities and classify different types of cyber attacks using well-known benchmark datasets.

---

## Table of Contents

- Introduction  
- Dataset Overview  
- Methodology  
- Model Development  
- Model Evaluation  
- Results and Discussion  
- Challenges and Limitations  
- Conclusion  
- License  

---

## Introduction

With the rapid growth of network-based applications, cybersecurity threats have become more complex and frequent. Traditional intrusion detection systems often fail to detect advanced or unknown attacks.  
This project leverages Machine Learning and Deep Learning approaches to build a robust and intelligent Network Intrusion Detection System capable of identifying both normal and malicious network traffic.

---

## Dataset Overview

The project uses two widely recognized datasets for intrusion detection research:

### NSL-KDD Dataset
NSL-KDD is an improved version of the KDD’99 dataset. It removes redundant records and provides a more balanced dataset, making evaluation more reliable and realistic.

### UNSW-NB15 Dataset
UNSW-NB15 is a modern dataset that includes contemporary normal activities and attack behaviors, allowing models to learn realistic and diverse intrusion patterns.

---

## Methodology

### Data Preprocessing
- Loading datasets using Python libraries such as Pandas and NumPy  
- Removing irrelevant or redundant features  
- Encoding categorical features  
- Normalizing numerical data  
- Splitting data into training and testing sets  

### Feature Identification
Features are categorized into:
- Connection-based features  
- Content-based features  
- Traffic-based statistical features  
- Label features (normal or attack)

---

## Model Development

### Machine Learning Models
The following ML algorithms are implemented and evaluated:
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Logistic Regression  

### Deep Learning Models
Deep Learning models are used to capture complex patterns in network traffic:
- Convolutional Neural Network (CNN)  
- Recurrent Neural Network (RNN) *(planned)*  
- Long Short-Term Memory (LSTM) *(planned)*  

---

## Model Evaluation

### Binary Classification
- Classifies traffic as **Normal** or **Attack**
- Metrics used: Accuracy, Precision, Recall, F1-score

### Multiclass Classification
- Classifies attacks into categories such as:
  - DoS
  - Probe
  - R2L
  - U2R
- Evaluation using confusion matrix and classification report

---

## Results and Discussion

The experimental results compare different ML and DL models to identify the best-performing algorithms. The analysis highlights trade-offs between accuracy, computational complexity, and scalability.

---

## Challenges and Limitations

- Deep learning models require more computational resources  
- Dataset imbalance can affect model performance  
- Some deep learning implementations are still under development  

---

## Conclusion

This project demonstrates the effectiveness of Machine Learning and Deep Learning techniques in improving network intrusion detection. With further optimization and real-time deployment, the system can serve as a strong foundation for intelligent cybersecurity solutions.

---

