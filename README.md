# 🏥 Medical Insurance Price Prediction using Linear Regression

## 📌 Project Overview

This project predicts **medical insurance charges** using **Linear Regression**. The objective is to understand how different factors such as age, BMI, sex, and smoking habits affect medical insurance costs.

The project includes both:
- **Simple Linear Regression** (using Age)
- **Multiple Linear Regression** (using Age, BMI, Sex, and Smoker)

---

## 🎯 Problem Statement

Insurance companies determine medical insurance charges based on several customer characteristics. The goal of this project is to build regression models that can estimate insurance charges for new customers.

---

## 📂 Dataset

- **Dataset:** Medical Insurance Dataset
- **Target Variable:** `charges`

### Features Used

| Feature | Description |
|----------|-------------|
| age | Age of the customer |
| bmi | Body Mass Index |
| sex | Gender |
| smoker | Smoking status |
| charges | Medical insurance charges |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The following analysis was performed:

- Dataset overview
- Missing value check
- Data type analysis
- Scatter plots
- Feature selection

---

## ⚙️ Data Preprocessing

- Label Encoding
- Train-Test Split
- Feature Selection

---

# 📈 Model 1 — Simple Linear Regression

### Input Feature
- Age

### Output
- Insurance Charges

### Results

| Metric | Value |
|--------|-------|
| MAE | 9157.84 |
| MSE | 135232181.05 |
| RMSE | 11628.94 |
| R² Score | 0.093 |

### Observation

Using only **Age** provides poor prediction accuracy because insurance charges depend on multiple factors.

---

# 📈 Model 2 — Multiple Linear Regression

### Input Features

- Age
- BMI
- Sex
- Smoker

### Output

- Insurance Charges

### Results

| Metric | Value |
|--------|-------|
| MAE | 4207.69 |
| MSE | 34444141.49 |
| RMSE | 5868.91 |
| R² Score | 0.765 |

### Observation

Including multiple relevant features significantly improved the prediction performance compared to the simple linear regression model.

---

## 📉 Model Evaluation Metrics

The following evaluation metrics were used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📌 Conclusion

- Simple Linear Regression using only Age was not sufficient for accurate prediction.
- Multiple Linear Regression achieved much better performance.
- Smoking status had the greatest impact on insurance charges.
- Multiple features provide a much more reliable prediction than a single feature.

---


## 👨‍💻 Author

**Sripraharsha Reddy**

B.Tech Student | Aspiring AI Engineer

GitHub: https://github.com/sripraharsha12
