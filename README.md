# 🌸 ML Iris Classification

A simple machine learning project to classify Iris flower species using classic supervised learning algorithms. This project uses the well-known **Iris dataset** to demonstrate classification models and evaluate their performance.

---

## 📌 Project Overview

This project aims to classify iris flowers into one of three species:

- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

based on four features:

- Sepal length
- Sepal width
- Petal length
- Petal width

---

## 🧠 Machine Learning Workflow Applied

1. **Data Loading**  
   Load the Iris dataset using `sklearn.datasets`.

2. **Data Exploration & Visualization**  
   Understand data distribution using:
   - Pandas & NumPy
   - Seaborn pairplots
   - Correlation heatmaps

3. **Data Preprocessing**
   - Drop unnecessary columns
   - Train/test split

4. **Model Training**  
   Compare different ML algorithms:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Random Forest

5. **Evaluation**  
   Used accuracy, confusion matrix, and classification reports to evaluate models.

---

## 📁 Project Structure
```bash
.
├── data
│   └── Iris.csv
├── main.ipynb
└── README.md

2 directories, 3 files
```
---

## 📊 Results
After training and evaluating multiple machine learning models on the Iris dataset, here are the accuracy scores and classification performance for each:

| Model                   | Accuracy (%) |
|-------------------------|--------------|
| K-Nearest Neighbors (KNN)      | 94.74%       |
| Logistic Regression            | 97.37%       |
| Random Forest Classifier       | 94.74%       |

Therefore I used Logistic Regression and fine-tuned to get the final accuracy as 97%.

## 💡 Future Improvements
- Model explainability with SHAP or LIME
- Deploy model with Streamlit or Flask