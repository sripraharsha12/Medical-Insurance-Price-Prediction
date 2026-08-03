# 🏥 Medical Insurance Price Prediction using Linear Regression

## 📌 Project Overview

This project predicts **medical insurance charges** using **Linear Regression** by analyzing customer information such as age, BMI, gender, smoking status, and the number of children.

The project demonstrates the complete Machine Learning workflow, from data exploration and preprocessing to model training, evaluation, and prediction.

This notebook includes:

- 📈 Simple Linear Regression (using Age)
- 📈 Multiple Linear Regression (using Age, BMI, Sex, and Smoker)

---

# 🎯 Problem Statement

Medical insurance companies estimate insurance charges based on several personal and health-related factors.

The objective of this project is to build Linear Regression models that can accurately predict insurance charges for new customers using historical data.

---

# 📂 Dataset

**Dataset:** Medical Insurance Dataset

**Target Variable:** `charges`

### Features

| Feature | Description |
|---------|-------------|
| age | Age of the customer |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance charges (Target Variable) |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis (EDA)

The following analysis was performed:

- Dataset overview
- Missing value analysis
- Duplicate value check
- Feature distributions
- Correlation analysis
- Feature relationship visualization

---

# ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Label Encoding
- Feature Selection
- Train-Test Split

---

# 📈 Model 1 — Simple Linear Regression

### Input Feature

- Age

### Target

- Insurance Charges

## Evaluation Results

| Metric | Value |
|---------|--------|
| MAE | 9157.84 |
| MSE | 135232181.05 |
| RMSE | 11628.94 |
| R² Score | 0.093 |

### Observation

Using only **Age** results in poor prediction accuracy because insurance charges depend on multiple customer attributes.

---

# 📈 Model 2 — Multiple Linear Regression

### Input Features

- Age
- BMI
- Sex
- Smoker
- Charges
- Region

### Target

- Insurance Charges

## Evaluation Results

| Metric | Value |
|---------|--------|
| MAE | 4181.81 |
| MSE | 38940169.92 |
| RMSE | 6240.20 |
| R² Score | 0.772 |

### Observation

Using multiple relevant features significantly improved prediction performance compared to the simple linear regression model.

---

# 📏 Evaluation Metrics

The following regression metrics were used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# ✅ Conclusion

This project demonstrates the complete Machine Learning workflow using Linear Regression.

### Key Takeaways

- Simple Linear Regression using only **Age** was insufficient for accurate prediction.
- Multiple Linear Regression significantly improved model performance.
- Smoking status was one of the most influential factors affecting insurance charges.
- Using multiple features produces much more reliable predictions than relying on a single feature.

---

# 📚 Future Improvements

- Feature Engineering
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Hyperparameter Tuning
- Model Deployment using FastAPI

---

# 👨‍💻 Author

**Sripraharsha Reddy**

🎓 B.Tech Student | Aspiring AI Engineer

🔗 GitHub: https://github.com/sripraharsha12