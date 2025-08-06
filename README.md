# data-analysis-internship-task-4
#  House Price Prediction using Linear Regression

This project is an end-to-end implementation of a **House Price Prediction** model using **Linear Regression**. The goal is to predict house prices based on features like area (in sq. ft), number of rooms, and location.

---

## 📌 Project Overview

- Load and explore the dataset
- Handle missing values and outliers
- Normalize numerical features
- Encode categorical variables using one-hot encoding
- Perform correlation analysis
- Train a **Linear Regression** model
- Evaluate model performance using MSE, RMSE, and R² Score
- Visualize predictions and feature importance

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – for data manipulation
- **Matplotlib / Seaborn** – for data visualization
- **Scikit-learn** – for machine learning model and evaluation

---

## 📂 Dataset

The dataset `house_prices.csv` contains the following columns:

| Column Name     | Description                          |
|------------------|--------------------------------------|
| `Size(in sq)`     | Area of the house in square feet     |
| `NumRooms`        | Number of rooms                      |
| `Location`        | Location of the property (categorical) |
| `Price`           | Target variable – price of the house |

---

## 🔍 Exploratory Data Analysis

- Distribution plots and boxplots for numerical features
- Correlation matrix to understand feature relationships
- Heatmap visualization for better insights

---

## ⚙️ Preprocessing

- **Missing Values**: Checked and optionally filled (if needed)
- **Scaling**: Applied Min-Max scaling to `Size(in sq)` and `NumRooms`
- **Encoding**: One-Hot Encoding applied to `Location` column

---

