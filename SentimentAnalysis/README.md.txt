# 📊 Sentiment Analysis using TF-IDF and Logistic Regression

## 📌 Dataset Description
- **review**: Customer review text  
- **sentiment**: Sentiment label (`positive` or `negative`)  
- **Total entries**: 50  
  - 25 Positive  
  - 25 Negative  

## ✅ Model
- **Task**: Binary Sentiment Classification (NLP)
- **Preprocessing**:
  - Converted text to lowercase
  - Vectorized text using **TF-IDF** (`TfidfVectorizer`)
- **Model**: Trained a **Logistic Regression Classifier** using `scikit-learn`
- **Label Encoding**:
  - `positive` → 1
  - `negative` → 0
- **Dataset Split**: 80% Training / 20% Testing using `train_test_split`

## 📊 Evaluation
- **Accuracy Score**
- **Classification Report**:
  - Precision
  - Recall
  - F1-score
- **Visualization**:
  - Confusion Matrix (optional, with seaborn heatmap)

## 💻 Libraries Used
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## 📁 Files
- `SentimentAnalysis.ipynb`: Main Jupyter notebook
- `cust_reviews.csv`: Dataset of 50 reviews

---

> This project performs basic sentiment analysis on customer reviews using a classical machine learning pipeline with TF-IDF vectorization and Logistic Regression.
