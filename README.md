# 🌳 Decision Tree Regression on the Diabetes Dataset

A small Machine Learning project that predicts diabetes disease progression using a **Decision Tree Regressor** built with **Scikit-learn**. The small project includes data exploration, model training, hyperparameter tuning, evaluation, visualization, and model serialization.

---

## 🚀 Features

- 📊 Data exploration using Pandas
- 🌳 Decision Tree Regression
- ⚙️ Hyperparameter tuning with GridSearchCV
- 📈 Model evaluation using regression metrics
- 🎨 Decision Tree visualization
- 💾 Model serialization using Joblib

---

## 📁 Dataset

This project uses the **Diabetes Dataset** available in Scikit-learn.

- **Source:** `sklearn.datasets.load_diabetes()`
- **Samples:** 442
- **Features:** 10
- **Target:** Quantitative measure of disease progression one year after baseline.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```text
Decision-Tree-Diabetes/
│
├── DecisionTree.ipynb
├── decision_tree.joblib
├── requirements.txt
├── README.md
└── images/
```

---

## 📊 Model Evaluation

The model was evaluated using standard regression metrics such as:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 💾 Saving the Model

The trained model is serialized using **Joblib**.


