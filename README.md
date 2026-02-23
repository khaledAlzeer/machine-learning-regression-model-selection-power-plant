# 🔥 Regression Model Selection – Power Plant Dataset

This project presents a complete comparison of five regression models applied to a real-world power plant dataset.

## 📊 Dataset Information

- 9,569 rows (including header)
- 4 input features:
  - AT (Ambient Temperature)
  - V (Exhaust Vacuum)
  - AP (Ambient Pressure)
  - RH (Relative Humidity)
- Target variable:
  - PE (Power Output)

The objective is to predict the power output (PE) based on environmental conditions.

---

## 🤖 Models Implemented

1. Multiple Linear Regression
2. Polynomial Regression (Degree = 4)
3. Support Vector Regression (RBF Kernel)
4. Decision Tree Regression
5. Random Forest Regression

---

## 📈 Model Performance (R² Score)

| Model | R² Score |
|--------|----------|
| Multiple Linear Regression | 0.9325 |
| Polynomial Regression | 0.9455 |
| SVR | 0.9481 |
| Decision Tree | 0.9229 |
| Random Forest | **0.9616** |

🏆 Random Forest achieved the best performance.

---

## 🧠 Concepts Covered

- Train/Test Split
- Feature Scaling
- Polynomial Feature Engineering
- Model Comparison
- Overfitting
- Regularization
- Model Evaluation (R² Score)

---

## ⚙️ Tools Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📌 Future Improvements

- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Cross-validation
- Feature importance analysis
