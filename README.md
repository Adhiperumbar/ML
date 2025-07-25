# ML
# 🏡 House Price Prediction Using Machine Learning
🔗 [Project Repository](https://github.com/Adhiperumbar/ML)

This project uses the Ames Housing dataset to build and compare multiple regression models for predicting house prices. It includes data preprocessing, model training, evaluation, and feature importance analysis.

## 🔍 Problem Statement

Accurately predicting house prices based on various features like area, quality, neighborhood, etc., can assist buyers, sellers, and real estate professionals in making informed decisions.

---

## 📁 Dataset

- **Source**: Ames Housing Dataset
- **Link**: [Kaggle - Ames Housing](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- **Features**: 82 attributes including lot size, number of rooms, garage type, etc.

---

## 📊 ML Models Used

- **Linear Regression**  
- **Random Forest Regressor**  
- **XGBoost Regressor**

---

## ⚙️ Workflow

1. Load and clean data
2. Handle missing values
3. Encode categorical variables
4. Train-test split
5. Model training and comparison
6. Feature importance visualization
7. Save best model using `joblib`

---

## ✅ Evaluation Metric

- **Root Mean Squared Error (RMSE)**
- **R² Score**

---

## 📈 Results

| Model               | RMSE ↓      | R² Score ↑ |
|--------------------|-------------|------------|
| Linear Regression  | ~28,000     | ~0.85      |
| Random Forest       | ~22,000     | ~0.89      |
| XGBoost             | **~20,000** | **0.91**   |

---

## 🔍 Feature Importance (Top Features)
- `OverallQual`  
- `GrLivArea`  
- `TotalBsmtSF`  
- `GarageCars`  
- `1stFlrSF`

---

## 💾 Save and Reuse Model

- Model saved using `joblib` as `xgb_model.pkl`
- Can be loaded for prediction without retraining

---

## 💡 Future Work

- Build a Streamlit web app for live predictions
- Hyperparameter tuning with `GridSearchCV`
- Add more feature engineering

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Scikit-learn
- XGBoost, Random Forest
- Matplotlib, Seaborn
- Google Colab
