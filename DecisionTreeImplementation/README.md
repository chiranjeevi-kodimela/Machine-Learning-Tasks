
# 🌳 Decision Tree Classification using scikit-learn

## ✅ Objective

To build and visualize a **Decision Tree Classifier** using **scikit-learn** that predicts whether a student will **pass** or **fail** based on their study habits, sleep schedule, and class attendance.

---

## 🔍 Problem Statement

Given a dataset of student academic features, the goal is to create a model that can predict **pass/fail outcome** using decision rules learned from training data.

---

## 🧠 Methodology

We use a **Decision Tree Classifier** that:
- Splits data based on Gini impurity or information gain
- Learns decision paths based on:
  - Hours studied
  - Sleep hours
  - Attendance level (minimum, low, avg, high)
- Visualizes the tree structure and feature importance

---

## 📦 Dataset: `students_data.csv`

- Total records: **150 students**
- Columns:
  - `hours_studied`: Hours of study per day (0–10)
  - `sleep_hours`: Sleep duration (4–9 hours)
  - `attendance`: Attendance level (`minimum`, `low`, `avg`, `high`)
  - `pass`: Target label (`yes`, `no`)
- Balanced Dataset:
  - 75 students → `pass = yes`
  - 75 students → `pass = no`

---

## 🔧 Implementation Steps

1. **Upload Dataset** using Google Colab file upload
2. **Import Libraries** (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`)
3. **Preprocess**:
   - Encode categorical features using `LabelEncoder`
4. **Split Dataset** into training and testing sets (80-20)
5. **Train Model** using `DecisionTreeClassifier`
6. **Make Predictions** and evaluate performance
7. **Visualize**:
   - Full decision tree plot
   - Confusion matrix heatmap

---

## 📊 Evaluation Metrics

- **Accuracy Score**: Overall correctness of predictions
- **Classification Report**:
  - Precision, Recall, F1-score per class
- **Confusion Matrix**:
  - Visualizes predicted vs actual values
- **Tree Visualization**:
  - Shows the decision-making hierarchy learned by the model

---

## 🖼️ Sample Output

```text
✅ Accuracy Score: 0.90

📊 Classification Report:
              precision    recall  f1-score   support
         no       0.88      0.93      0.90        15
        yes       0.93      0.87      0.90        15

    accuracy                           0.90        30
   macro avg       0.90      0.90      0.90        30
weighted avg       0.90      0.90      0.90        30
```

✅ Visual Output Includes:
- 🌲 Full Decision Tree Diagram
- 📉 Confusion Matrix Heatmap

---

## 📚 Libraries Used

```python
pandas
scikit-learn (tree, model_selection, preprocessing, metrics)
matplotlib.pyplot
seaborn
```

---

## 🚀 How to Run

1. Open the provided `.ipynb` notebook in **Google Colab**
2. Upload the `students_data.csv` file when prompted
3. Run all cells sequentially
4. View accuracy, classification report, and visualizations

---

## ✅ Conclusion

This project demonstrates how a **Decision Tree** can effectively classify student academic outcomes based on basic features. It also showcases how to evaluate and visualize tree-based models using scikit-learn. The project is ideal for beginners in **machine learning** and **model interpretability**.

---

## ✨ Optional Extensions

- Replace the dataset with real academic data (e.g., Kaggle datasets)
- Tune hyperparameters (`max_depth`, `criterion`) for better accuracy
- Compare with **Random Forest**, **KNN**, or **Logistic Regression**
- Export the trained model using `joblib` or `pickle`

---

## 🙌 Credits

Developed as part of a submission for **CodTech Internship**

Created using **Google Colab**
