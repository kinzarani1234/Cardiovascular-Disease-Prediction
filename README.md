# Cardiovascular Disease Prediction using Machine Learning 🫀

This project applies various machine learning algorithms to predict cardiovascular disease using patient medical data. The goal is to build an accurate classification model by analyzing important health features.

---

## 📊 Dataset

- 📎 **Source:** [Cardiovascular Disease Dataset – Kaggle](https://www.kaggle.com/datasets/akshatshaw7/cardiovascular-disease-dataset)
- 💡 This dataset includes patient records such as age, gender, blood pressure, cholesterol, glucose, physical activity, and more.
- 🎯 Target Variable: `cardiovascular_disease` (1 = has disease, 0 = no disease)

---

## 🔍 Exploratory Data Analysis (EDA)

- Visualized distributions of numerical and categorical features
- Performed correlation analysis using a heatmap
- Identified and removed outliers using boxplots
- Checked data imbalance and feature relationships with the target

---

## 🧹 Data Preprocessing

- Removed duplicates
- Feature scaling using `StandardScaler` (applied after train-test split)
- Selected important features using `SelectKBest`
- Split data into training and test sets (80/20)

---

## 🤖 Models Applied

| Model               | Accuracy (%) |
|---------------------|--------------|
| Logistic Regression | 72.71        |
| Random Forest       | 68.78        |
| XGBoost             | 73.09        |
| Decision Tree       | 64.58        |
| K-Nearest Neighbors | 69.19        |
| Naive Bayes         | 71.03        |
| Gradient Boosting   | **73.26**    |

📌 **Best Performing Model**: `Gradient Boosting` with 73.26% accuracy — slightly better than XGBoost.


---

## 📁 Project Structure

```bash
.
├── cardiovascular_disease.ipynb   # Main notebook with full analysis and models
├── requirements.txt                  # List of required libraries
├── README.md                         # Project documentation

```



## 👩‍💻 Author
**Kinza Rani**

Data Scientist & AI Enthusiast

