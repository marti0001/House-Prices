# 🏠 House Price Prediction | Advanced Regression Techniques

## 📌 Project Overview  

The **House Prices: Advanced Regression Techniques** competition on Kaggle challenges participants to predict house prices based on a rich dataset of housing features. This project focuses on **data analysis, preprocessing pipelines, model selection, and ensemble learning techniques** to maximize prediction accuracy.  

---

## 🚀 Key Features  

### 🔎 1. Task Analysis  
✔️ In-depth exploration of the dataset structure, input features, and target variable.  
✔️ Understanding key variables affecting house prices.  

### 🛠️ 2. Data Preparation  
✔️ **Handling Missing Values:**  
   - Categorical variables filled with `"None"` to preserve category integrity.  
✔️ **Feature Transformation:**  
   - **Categorical Features:** One-Hot Encoding.  
   - **Numerical Features:** Standardization for better model performance.  
✔️ **Data Splitting:**  
   - Created **training** and **validation** sets for model evaluation.  

### 🔄 3. Automated Pipelines  
✔️ **Pipeline for Numerical Features:** Standardization.  
✔️ **Pipeline for Categorical Features:** One-Hot Encoding.  
✔️ Integrated pipelines with models for seamless training workflow.  

### 🧠 4. Model Building & Hyperparameter Tuning  
✔️ **Baseline Model:** Linear Regression.  
✔️ **Advanced Regression Models:**  
   - **GridSearchCV & RandomizedSearchCV** applied to:  
     - Ridge Regression  
     - RandomForestRegressor  
     - XGBRegressor  
     - GradientBoostingRegressor  
     - LGBMRegressor  
     - CatBoostRegressor  

### 🔗 5. Advanced Ensemble Learning  
✔️ **Voting Regressor:** Combines multiple models for improved predictions.  
✔️ **Stacking Regressor:** Uses base models with a meta-model for final prediction.  

---

## 🏗️ Project Structure

```bash
MNIST/
├── 📁 input/              
│   ├── 📄 data_description.txt        
│   ├── 📄 sample_submission.csv       # Sample submission 
│   ├── 📄 test.csv                    # Test dataset
│   └── 📄 train.csv                   # Training dataset
│
├── 📁 notebooks/                      # Jupyter notebooks
│   └── 📘 HS_01_House Prices.ipynb    # Complete analysis
│
└── 📁 output/                         
     └── 📄 submission_HS_01.csv       # submission predict

```
---

## 🛠️ Technologies & Tools  

| Category             | Tools / Libraries |
|----------------------|------------------|
| **Programming**      | Python 3.8+ |
| **Data Processing**  | Pandas, NumPy |
| **Machine Learning** | Scikit-learn, XGBoost, LightGBM, CatBoost |
| **Visualization**    | Matplotlib, Seaborn |

---

### 🏆 Results
**Achieved Top 844** on Kaggle leaderboard using stacked ensemble models.

---