# Flight Price Prediction using Machine Learning

This project focuses on predicting flight ticket prices using machine learning techniques.  
The dataset undergoes extensive feature engineering, handling of categorical variables, and preprocessing to make it suitable for model training.

---

##  Project Overview

Airline ticket prices vary based on multiple factors such as airline, route, stops, duration, and timing.  
This project aims to build a regression-based ML model that accurately predicts flight prices using these features.

---

##  Features & Feature Engineering

The following preprocessing steps were performed:

###  Date & Time Features
- Extracted **Date, Month, Year**
- Extracted **Departure Hour & Minute**
- Extracted **Arrival Hour & Minute**
- Converted **Duration** into hours and minutes

###  Categorical Encoding
- Applied **One-Hot Encoding** to nominal features:
  - Airline
  - Source
  - Destination
  - Additional_Info
- Converted boolean dummy variables to **0/1**

###  Ordinal Encoding
- **Total_Stops** treated as an ordinal feature (0, 1, 2 stops)

###  Data Cleaning
- Handled missing values
- Converted all columns to numeric types
- Ensured dataset is fully ML-ready

---

##  Final Dataset Characteristics
- All features are numeric
- No object-type columns
- No missing values
- Suitable for regression models

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook



