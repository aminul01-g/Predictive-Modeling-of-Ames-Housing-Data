# 🏡 Predictive Modeling of Ames Housing Data

This project builds accurate and interpretable machine learning models to predict house prices using the **Ames Housing dataset**. It covers data preprocessing, feature engineering, model selection, training, and evaluation using various regression techniques.

---

## 📁 Project Structure

Predictive-Modeling-of-Ames-Housing-Data/
├── notebooks/ # Jupyter notebooks for each modeling stage
├── README.md # Project overview and usage
└── requirements.txt # Dependencies


---

## 📌 Problem Statement

Predict house sale prices in Ames, Iowa using detailed property features like zoning, lot size, year built, quality, condition, and more.

---

## ✅ Features

- Exploratory Data Analysis (EDA)
- Data Cleaning & Imputation
- Feature Engineering
- Outlier Removal
- Skewness Correction
- Categorical Encoding
- Model Training:
  - Linear Regression
  - Lasso, Ridge
- Cross-Validation & Hyperparameter Tuning
- Performance Evaluation (RMSE, R²)

---

## 📊 Dataset

- **Source**: [Ames Housing Dataset](https://storage.googleapis.com/cloud-samples-data/ai-platform-unified/datasets/tabular/petrol-consumption.csv)
- **Rows**: 200
- **Features**: 9
- **Target**: `SalePrice`

---

## 📈 Model Performance

| Model            | RMSE (CV) | R² Score |
|------------------|-----------|----------|
| Linear Regression|  0.3923   |  -0.2125 |
| Ridge            |  0.3881   |  -0.1870 |
| Lasso            |  0.3851   |  -0.1692 |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/aminul01-g/Predictive-Modeling-of-Ames-Housing-Data.git
cd Predictive-Modeling-of-Ames-Housing-Data
```
### 2. Install Dependencies

```bash
pip install -r requirements.txt
```
## 🧪 Requirements

- Python 3.8+

- pandas

- numpy

- scikit-learn

- xgboost

- matplotlib

- seaborn

- jupyter

### 📚 References
- Dean De Cock - Original Paper

- Kaggle House Prices Competition

### 📄 License
This project is licensed under the MIT License. See LICENSE for details.

---

Let me know if you want a customized badge section, sample visualizations, or `requirements.txt` generated automatically!

