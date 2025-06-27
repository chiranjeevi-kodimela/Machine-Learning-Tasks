# 🎬 Movie Recommendation System

## ✅ Objective

To build a **Recommendation System** using **Collaborative Filtering** and **Matrix Factorization** (SVD) that predicts movie ratings for users and recommends top-rated movies.

---

## 🔍 Problem Statement

Given a dataset of movie ratings by users, predict how a user would rate a movie they haven’t seen and recommend the top-N movies they are most likely to enjoy.

---

## 🧠 Methodology

We use **Singular Value Decomposition (SVD)**, a matrix factorization technique that:
- Decomposes the user-item rating matrix into latent features
- Learns patterns of user preferences and item characteristics
- Predicts ratings for unrated items using the learned latent factors

---

## 📦 Dataset: MovieLens 100K

- Built-in dataset provided by `surprise` library
- Contains 100,000 movie ratings by 943 users on 1682 movies
- Ratings are on a scale of 1 to 5

---

## 🔧 Implementation Steps

1. **Install and Import Libraries**
2. **Load the MovieLens Dataset**
3. **Split Dataset into Training and Testing Sets**
4. **Train an SVD-based Recommendation Model**
5. **Evaluate Performance using RMSE**
6. **Generate Top-N Movie Recommendations for a Specific User**

---

## 📊 Evaluation Metric

- **RMSE (Root Mean Squared Error)** is used to measure how closely predicted ratings match the actual ratings.
- Lower RMSE indicates better predictive accuracy.

---

## 🎯 Recommendation Output

For any user (e.g., User ID = 196), the model recommends the **Top 5 movies** the user hasn't rated yet, sorted by predicted rating.

---

## 🙌 Credits

Developed as part of a submission for CodTech Internship 

Created using Google Colab

---
## ✅ Conclusion

This notebook demonstrates how Collaborative Filtering with Matrix Factorization (SVD) can be effectively used to build a personalized movie recommendation engine. The approach is scalable and can be extended to other domains like books, music, products, etc.

---


