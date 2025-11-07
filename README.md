# Flight Delay Prediction

## Overview
This project analyzes and predicts **flight delays** using machine learning techniques applied to historical flight data.  
The notebook explores the relationship between different flight parameters — such as departure time, carrier, origin, and weather conditions — and delay occurrences to build predictive models capable of identifying potential delays before takeoff.

## Objectives
- Perform **Exploratory Data Analysis (EDA)** to uncover patterns in flight delays  
- Preprocess and clean raw flight data  
- Engineer meaningful features such as time of day, airline performance, and distance bins  
- Train and evaluate multiple **machine learning models** for delay prediction  
- Compare model performance using accuracy, precision, recall, and F1-score  

## Methodology
1. **Data Preprocessing:** Handle missing values, encode categorical variables, and scale features  
2. **EDA:** Visualize delay distributions, carrier performance, and temporal trends  
3. **Feature Engineering:** Create new features based on flight time, weekday, and distance  
4. **Model Training:** Logistic Regression, Decision Tree, Random Forest, and XGBoost  
5. **Model Evaluation:** Confusion matrix, ROC-AUC, and classification metrics  

## Technologies Used
- **Python 3**
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `datetime`
- **Environment:** Jupyter Notebook / Google Colab

## Key Insights
- Departure time and weather are strong predictors of delay likelihood  
- Certain airlines and airports consistently show higher delay frequencies  
- Ensemble methods like **Random Forest** and **XGBoost** outperform linear classifiers  
