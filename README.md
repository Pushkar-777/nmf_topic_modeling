# NMF Topic Modeling for News Articles

A Natural Language Processing project that uses **Non-Negative Matrix Factorization (NMF)** to discover hidden topics in news articles and automatically classify new articles into meaningful topic categories.

## 🚀 Project Overview

This project processes news article text, cleans and preprocesses the data, applies TF-IDF vectorization, and uses NMF to identify major topics.

The model identifies these topics:

- 🛒 Business & Retail
- 🛢️ Oil & Energy
- 📈 Economy & Finance
- 👥 People & Employment
- ✈️ Airlines & Travel

It also includes an interactive interface where users can enter a new article and get its predicted topic.

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- TF-IDF
- NMF (Non-Negative Matrix Factorization)
- Google Colab

## ⚙️ Workflow

1. Load the news article dataset
2. Perform data exploration and validation
3. Clean and preprocess text
4. Remove stopwords
5. Convert text into TF-IDF features
6. Apply NMF topic modeling
7. Extract important words from each topic
8. Assign meaningful names to discovered topics
9. Predict topics for new articles
10. Test the model using sample articles

## 📊 Example

**Input:**

> Oil prices are increasing as major producers discuss changes in production and global energy demand.

**Predicted Topic:**

`Oil & Energy`

## 📁 Project Structure

```text
nmf_topic_modeling/
│
├── NMF_Topic_Modeling.ipynb
├── README.md
└── requirements.txt
