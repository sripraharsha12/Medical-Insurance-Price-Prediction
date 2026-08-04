# 🏥 Medical Insurance Price Prediction using Linear Regression

## 📖 About the Project

This project is one of the first milestones in my hands-on Machine Learning journey.

The goal of this project is to predict medical insurance charges based on customer information such as age, BMI, gender, smoking status, number of children, and region using Linear Regression.

While working on this project, I learned that Machine Learning is much more than simply training a model. It starts with understanding the problem, exploring the dataset, cleaning and preprocessing the data, selecting useful features, building models, evaluating performance, and finally making predictions on new data.

One of the most valuable parts of this project was comparing **Simple Linear Regression** with **Multiple Linear Regression**. It clearly showed how adding more relevant features can significantly improve prediction performance.

---

# 🎯 Problem Statement

Medical insurance companies estimate insurance charges based on several personal and health-related factors.

The objective of this project is to build a Machine Learning model that can estimate insurance charges using customer information and understand which features have the greatest impact on insurance costs.

---

# 📂 Dataset

**Dataset:** Medical Insurance Dataset

**Target Variable:** `charges`

### Features

| Feature | Description |
|----------|-------------|
| age | Customer's Age |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of Children |
| smoker | Smoking Status |
| region | Residential Region |
| charges | Medical Insurance Charges (Target Variable) |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis (EDA)

Before building the model, I explored the dataset to better understand the data and identify important patterns.

The analysis included:

- Dataset Overview
- Missing Value Analysis
- Duplicate Value Check
- Feature Distributions
- Correlation Heatmap
- Relationship between Features and Insurance Charges

This step helped me understand which features influence insurance charges the most.

---

# ⚙️ Data Preprocessing

The following preprocessing techniques were applied before training the model:

- Label Encoding
- Feature Selection
- Train-Test Split

---

# 📈 Model 1 – Simple Linear Regression

### Feature Used

- Age

### Target Variable

- Insurance Charges

## Evaluation Results

| Metric | Value |
|---------|--------|
| MAE | 9157.84 |
| MSE | 135232181.05 |
| RMSE | 11628.94 |
| R² Score | 0.093 |

### Observation

Using only **Age** was not sufficient to accurately predict insurance charges because medical expenses depend on multiple factors.

---

# 📈 Model 2 – Multiple Linear Regression

### Features Used

- Age
- BMI
- Sex
- Smoker

### Target Variable

- Insurance Charges

## Evaluation Results

| Metric | Value |
|---------|--------|
| MAE | 4207.69 |
| MSE | 34444141.49 |
| RMSE | 5868.91 |
| R² Score | 0.771 |

### Observation

Adding multiple relevant features significantly improved the model's performance compared to Simple Linear Regression.

While experimenting with different feature combinations and preprocessing techniques, I also learned that improving a Machine Learning model is not only about increasing the evaluation score. The performance of a Linear Regression model also depends on the nature of the dataset and whether the relationship between the input features and the target variable is linear.

This project helped me understand both the strengths and limitations of Linear Regression and reinforced the importance of selecting the right algorithm for the problem.

---

# 📏 Model Evaluation

The models were evaluated using the following regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics helped compare both models and understand their overall performance.

---

# ✅ What I Learned

This project helped me understand the complete Machine Learning workflow, including:

- Understanding the business problem
- Exploring and preprocessing data
- Feature Selection
- Comparing Simple and Multiple Linear Regression
- Model Evaluation
- Making predictions using new customer data

Most importantly, I learned that building a good Machine Learning model is not just about training an algorithm. Understanding the data and selecting meaningful features plays an equally important role.

---

# 🚀 Future Improvements

Some improvements I plan to make in the future include:

- Feature Engineering
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Hyperparameter Tuning
- Streamlit Web Application
- Advanced Regression Models

---

# 👨‍💻 Author

**Sripraharsha Reddy**

B.Tech Student | Aspiring AI Engineer

I'm currently learning Artificial Intelligence and Machine Learning by building hands-on projects and continuously improving my skills.

🔗 GitHub: https://github.com/sripraharsha12