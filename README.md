# Apartment Rental Price Analysis

## Overview
This project explores the dynamics of apartment rental prices in the United States using data-driven techniques. By analyzing a dataset of over 10,000 apartment listings, the study investigates how factors such as apartment size, bedroom count, location, amenities, and pet policies affect rental prices. The goal is to understand key drivers of pricing and predict rental costs using machine learning models.  

The analysis shows that location and apartment size are the most influential factors, while amenities and pet policies play supporting roles. This provides insights for renters, landlords, and policymakers about what truly drives rental prices.

---

## Tech Stack & Libraries
- **Programming Language:** Python  
- **Data Analysis & Manipulation:** pandas, numpy  
- **Data Visualization:** matplotlib, seaborn, plotly  
- **Machine Learning & Modeling:** scikit-learn (Random Forest, Decision Tree, Linear Regression, Support Vector Regression)  
- **Data Preprocessing:** scikit-learn preprocessing (One-Hot Encoding, StandardScaler)  

---

## What Was Done
1. **Data Collection & Cleaning:**  
   - Used the UCI Apartment for Rent Classifieds dataset (U.S., 2019).  
   - Handled missing values and outliers.  
   - Encoded categorical variables and standardized numerical features for modeling.  

2. **Exploratory Data Analysis (EDA):**  
   - Examined distributions of rental prices and apartment sizes.  
   - Analyzed prevalence of amenities and pet policies.  
   - Investigated relationships between features (bedroom count, pet policies, amenities) and rental prices.  

3. **Predictive Modeling:**  
   - Built and compared multiple models: Random Forest, Decision Tree, Linear Regression, and Support Vector Regression.  
   - Evaluated models using R² and RMSE metrics.  
   - Determined feature importance to identify the most influential predictors of rent.  

---

## Key Results
- **Price Distribution:** Rental prices are right-skewed, with most listings in lower to mid-range and a few high-end luxury units.  
- **Influential Features:**  
  - **Bedrooms & Size:** Larger apartments consistently command higher rents.  
  - **Location:** Latitude, longitude, city, and state are top predictors of rent.  
  - **Amenities:** Limited direct impact; air conditioning slightly increases rent, while others mostly serve as context.  
  - **Pet Policy:** Pet-friendly apartments do not necessarily cost more; higher-priced units often have stricter policies.  
- **Predictive Modeling:**  
  - Random Forest achieved the best performance (R² ≈ 0.73, RMSE ≈ 312), capturing complex non-linear relationships.  
  - Linear Regression and SVR underperformed due to non-linear interactions between features.  

**Conclusion:** Apartment rental prices are primarily driven by location and size, while optional features like amenities and pet policies play secondary roles. Combining EDA with machine learning allows for both understanding market patterns and predicting rents with reasonable accuracy.
