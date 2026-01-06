# Financial-Sentiment-Analysis-Bullish-Bearish-Neutral
Machine learning project for automated financial news sentiment classification (Bullish / Bearish / Neutral).

# 📈 Financial Sentiment Analysis — Bullish | Bearish | Neutral

## 🧩 Problem Statement
Financial markets respond rapidly to news. Manual interpretation of financial headlines is slow, inconsistent, and difficult to scale.  
This project builds an automated NLP system that classifies financial news headlines into:
- Bullish (Positive)
- Bearish (Negative)
- Neutral

## 🎯 Business Objective
Develop a reliable sentiment classification model for financial news that improves trading, risk management, and investment analysis.

## 🗂 Dataset
Financial PhraseBank Dataset  
Fields: headline, sentiment (negative, neutral, positive)

## 🔍 Exploratory Data Analysis (EDA)
- Class distribution analysis
- Headline length distribution
- Frequent keyword extraction by sentiment
- Noise & outlier detection

## 🧹 Data Preprocessing
- Lowercasing
- Remove punctuation & numbers
- Stopword removal
- Lemmatization
- TF-IDF Vectorization (unigrams + bigrams)

## 🧠 Models Trained
- Logistic Regression
- Naive Bayes
- Linear SVM (Final Model)

## 📊 Model Evaluation

| Model | Accuracy | Macro F1 | Weighted F1 |
|------|---------|---------|-----------|
| Logistic Regression | 0.73 | 0.63 | 0.70 |
| Linear SVM | 0.75 | 0.68 | 0.74 |
| Naive Bayes | 0.71 | 0.56 | 0.67 |

### SVM Class-wise Performance

| Sentiment | Precision | Recall | F1 |
|---------|---------|-------|---|
| Negative | 0.64 | 0.52 | 0.57 |
| Neutral | 0.78 | 0.87 | 0.82 |
| Positive | 0.70 | 0.59 | 0.64 |

## 🏆 Final Model Recommendation
Linear SVM + TF-IDF

## 💼 Business Impact
- Faster detection of bullish/bearish sentiment
- Improved trading decisions
- Better risk management

## 🛠 Tech Stack
Python, Pandas, NumPy, NLTK, Scikit-learn, Matplotlib

## 👨‍💻 Author
Swaroop Narayan C S
