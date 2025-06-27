# 🎓 Predicting Student Academic Performance Using Socioeconomic and Psychological Factors

This project explores how linear regression can be used to predict student performance in **Mathematics** and **Portuguese** using the **UCI Student Performance Dataset**. It includes feature engineering, data preprocessing, custom gradient descent implementation, model evaluation, and interpretability through feature importance analysis.

---

## 📂 Dataset

The dataset is sourced from the **UCI Machine Learning Repository**:
- `student-mat.csv`: student performance in Mathematics
- `student-por.csv`: student performance in Portuguese
- Each file includes 33 attributes covering demographic, academic, behavioral, and socioeconomic features.

---

## 🎯 Objectives

- Predict final student grades (**G3**) using linear regression
- Compare model performance between Mathematics and Portuguese
- Implement and validate **gradient descent from scratch**
- Evaluate models using **R² score** and **MSE**
- Visualize **feature importance** to interpret results

---

## 🛠️ Technologies Used

- Python 3.x
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn

---

## 📊 Results

| Subject      | R² Score | Interpretation                        |
|--------------|----------|----------------------------------------|
| Mathematics  | 0.84     | Excellent – strong predictive power    |
| Portuguese   | 0.46     | Moderate – further feature engineering or nonlinear modeling recommended |

- Prior grades (**G1**, **G2**) were the most important predictors in both subjects.
- A custom gradient descent algorithm achieved results comparable to scikit-learn's `LinearRegression`.

---



