# 📊 Sales Prediction using Multiple Linear Regression

## 📌 Project Overview
This project focuses on predicting product sales based on advertising expenditures across different media channels such as TV, Radio, and Newspaper.

The goal is to understand how different advertising strategies impact sales and to build a predictive model using Multiple Linear Regression.

---

## 📂 Dataset Information
The dataset used in this project contains the following features:

- **TV** – Advertising budget spent on TV
- **Radio** – Advertising budget spent on Radio
- **Newspaper** – Advertising budget spent on Newspaper
- **Sales** – Resulting product sales (target variable)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Checked first few rows for initial understanding

### 2. Data Inspection
- Checked data types and missing values
- Understood dataset structure using `.info()`

### 3. Exploratory Data Analysis (EDA)
- Used pairplots to analyze relationships between features and sales
- Generated a correlation heatmap to understand feature dependencies

### 4. Model Building
- Applied **Multiple Linear Regression**
- Defined:
  - Independent variables: TV, Radio, Newspaper
  - Dependent variable: Sales

### 5. Feature Importance
- Extracted coefficients to understand impact of each feature
- Compared influence of different advertising channels

### 6. Feature Selection
- Built a model using only **TV and Radio**
- Compared performance with full model

### 7. Model Evaluation
- Used:
  - R² Score (for accuracy)
  - Mean Squared Error (for error measurement)

### 8. Train-Test Split
- Split dataset into training and testing sets
- Evaluated model performance on unseen data

---

## 📈 Key Insights
- TV and Radio advertising have a stronger impact on sales compared to Newspaper
- Removing less significant features can simplify the model without major performance loss
- Linear regression works well for this type of structured data

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
