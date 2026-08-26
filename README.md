# NMF Topic Modeling for News Articles

A Natural Language Processing project that uses **Non-Negative Matrix Factorization (NMF)** to discover hidden topics in news articles and automatically classify new articles into meaningful topic categories.

## 🚀 Project Overview

This project processes news article text, cleans and preprocesses the data, converts the text into numerical features using **TF-IDF Vectorization**, and applies **NMF Topic Modeling** to discover major topics.

The model identifies the following topics:

- 🛒 Business & Retail
- 🛢️ Oil & Energy
- 💰 Economy & Finance
- 👥 People & Employment
- ✈️ Airlines & Travel

The project also includes a simple interface where users can enter a new article and get its predicted topic.

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- TF-IDF Vectorization
- Non-Negative Matrix Factorization (NMF)

## 🔄 Project Workflow

```text
News Articles
     ↓
Data Loading
     ↓
Data Cleaning & Preprocessing
     ↓
Stopword Removal
     ↓
TF-IDF Vectorization
     ↓
NMF Topic Modeling
     ↓
Topic Identification
     ↓
New Article Classification
