# 📌 Sentiment Analysis of Persian Texts Using Deep Learning

This repository contains the code and experiments related to the thesis **"Sentiment Analysis of Persian Texts Using Deep Learning."** The primary goal of this research is to investigate the impact of various preprocessing techniques, word embedding methods, and deep learning models (**CNN and LSTM**) on sentiment analysis of Persian user reviews.

📖 **Author:** Mehdi Khodadadi  
🏫 **Institution:** Hamedan University of Technology  
📅 **Year:** 2025  

---

## 🔬 Experiments Overview

### 🟢 Experiment 1: Clustering-Based Sentiment Analysis  
- **Preprocessing**: Applied a complete pipeline after data cleaning.  
- **Word Embedding**: Used **FastText** for word representation.  
- **Dataset**: Unlabeled **Filimo dataset**.  
- **Clustering**: Applied to replace sentiment labels using the **Elbow method** and **Silhouette index**.  
- **Objective**: Evaluate the impact of clustering on data organization.  

### 🟢 Experiment 2: Supervised Sentiment Analysis  
- **Difference from Exp. 1**: Removed clustering and manually labeled data.  
- **Dataset**: 2,000 manually labeled reviews from **Filimo dataset** (balanced positive & negative).  
- **Models Used**: **CNN and LSTM** trained on labeled data.  
- **Objective**: Assess the effectiveness of **FastText embeddings** and compare models on structured labeled data.  

### 🟢 Experiment 3: Sentiment Analysis on Digikala Dataset  
- **Dataset**: Pre-labeled **Digikala dataset** (positive, negative, neutral).  
- **Word Embedding**: **FastText** used to capture semantic representations.  
- **Models Used**: **CNN and LSTM** applied on **20% of the dataset**.  
- **Objective**: Evaluate model efficiency on pre-labeled sentiment data.  

### 🟢 Experiment 4: Large-Scale Sentiment Analysis  
- **Dataset**: Pre-labeled **Digikala dataset** (positive, negative, neutral).  
- **Word Embedding**: **FastText** used for word vector representation.  
- **Models Used**: **CNN and LSTM** trained on **80% of the dataset**.  
- **Objective**: Compare model accuracy and effectiveness with a larger dataset.  

---

## ⚡ Key Features of This Repository  
✔ **Preprocessing Pipeline**: Data cleaning, tokenization, and normalization.  
✔ **Word Embeddings**: Implemented using **FastText** for improved semantic representation.  
✔ **Deep Learning Models**: CNN and LSTM architectures for sentiment analysis.  
✔ **Clustering Methods**: Applied in Experiment 1 to organize unlabeled data.  
✔ **Labeled Datasets**: Used in Experiments 2, 3, and 4 to evaluate supervised learning models.  

---

## 🚀 How to Use This Repository  

### 📌 Clone the Repository  
```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
