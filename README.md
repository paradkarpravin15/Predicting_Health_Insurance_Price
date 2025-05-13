# 🏥 Predicting Health Insurance Price

This project predicts individual health insurance charges based on past demographic and health-related data. It uses a linear regression machine learning model to understand and analyze how various factors influence insurance pricing.

---

## 📌 Problem Statement

Insurance companies need accurate models to determine premium amounts based on customer profiles. This project builds a predictive model to estimate insurance charges using real-world data and regression algorithms.

---

## 📊 Dataset Overview

The dataset contains the following features:

| Feature     | Description                                           |
|-------------|-------------------------------------------------------|
| `age`       | Age of the policyholder                               |
| `sex`       | Gender: male or female                                |
| `bmi`       | Body Mass Index                                       |
| `children`  | Number of children covered by the insurance           |
| `smoking_status`    | Smoking status (yes/no)                               |
| `location`    | Residential region in the US                          |
| `health_insurance_price`   | Final insurance cost (target variable)                |

---

## 🛠️ Technologies & Libraries Used

- **Python**
- **Machine Learning**
- **Pandas, NumPy** – Data handling and manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning modeling  
- **Google Colab** – Interactive coding environment

---

## 🔍 Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Identified columns, shape, datatypes & outliers
   - Summary statistics for numerical & categorical columns 
   - Visualized numerical & categorical distribution, correlation between numeric features, and numerical features to check for outliers
2. **Data Preprocessing**
   - Handling null values & duplicates
   - outlier treatment
   - Encoded categorical variables (`sex`, `smoking_status`, `location`)
   - Handled multicollinearity and feature interactions
4. **Model Building**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
5. **Model Evaluation**
   - R² Score
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)

---

## 📈 Key Insights

- **Smokers** pay significantly more for insurance than non-smokers.
- **BMI** is crucial in price prediction, especially when high.
- **Age** positively correlates with price, especially in older age groups.
- **Region** and **gender** have minimal impact on pricing.

---

## ✅ Results

- Achieved an R² Score of **`89%`** with the best model.
- Random Forest performed better than simple linear regression.
- Built an interpretable and deployable model for real-world applications.

---

## 🔗 Connect with Me

If you found this project interesting or have any feedback, feel free to connect:

📧 pravindparadkar2003@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/pravinparadkar/)  
