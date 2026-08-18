# 📊 Sales Prediction Using Python

## 📌 Overview

This project predicts product sales based on advertising budgets allocated to TV, Radio, and Newspaper using **Linear Regression**. It demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, visualization, and prediction.

This project was completed as **Task 4** of the **CODSOFT Data Science Internship**.

---

## 🎯 Objective

To build a machine learning model that predicts sales based on advertising expenditure across different media platforms.

---

## 📂 Dataset

The dataset contains the following features:

- **TV** – Advertising budget spent on TV
- **Radio** – Advertising budget spent on Radio
- **Newspaper** – Advertising budget spent on Newspaper
- **Sales** – Product sales (Target Variable)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📁 Project Structure

```
Task-4-Sales-Prediction/
│── advertising.csv
│── sales_prediction.py
│── README.md
│── requirements.txt
│── predictions.csv
│── feature_importance.csv
│── advertising_model.pkl
```

---

## 📊 Project Workflow

- Load and inspect the dataset
- Check for missing and duplicate values
- Perform Exploratory Data Analysis (EDA)
- Visualize correlations and feature relationships
- Split the dataset into training and testing sets
- Train a Linear Regression model
- Evaluate the model using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- Perform 5-Fold Cross Validation
- Predict sales for new advertising budgets
- Save predictions, feature importance, and trained model

---

## 📈 Visualizations

The project includes:

- Correlation Heatmap
- Pair Plot
- Sales Distribution
- TV vs Sales
- Radio vs Sales
- Newspaper vs Sales
- Feature Importance
- Actual vs Predicted Plot
- Residual Plot
- Residual Distribution

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/CODSOFT.git
```

Go to the project folder:

```bash
cd CODSOFT/Task-4-Sales-Prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python sales_prediction.py
```

---

## 📁 Generated Files

After execution, the following files are automatically created:

- `predictions.csv`
- `feature_importance.csv`
- `advertising_model.pkl`

---

## 📌 Machine Learning Model

**Algorithm:** Linear Regression

**Evaluation Metrics:**

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 🔮 Future Improvements

- Implement Random Forest Regression
- Implement XGBoost Regression
- Hyperparameter Tuning
- Deploy the model using Streamlit or Flask
- Add a web interface for predictions

---

## 👨‍💻 Author


**Pratham Gusain**

CODSOFT Data Science Internship – Task 4

---

## ⭐ Acknowledgements

This project was completed as part of the **CODSOFT Data Science Internship Program**.
