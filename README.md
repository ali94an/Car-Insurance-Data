# 🚗 Car Insurance Purchase Prediction
Ali Abu Nimah
## 📁 Project Overview

This project aims to predict whether a customer will purchase car insurance based on their personal, vehicle, and behavioral attributes. By leveraging machine learning techniques, the goal is to assist insurance companies in targeting potential customers more effectively, thereby optimizing marketing strategies and increasing conversion rates.

## 📊 Dataset Description

- **Source**: [Kaggle - Car Insurance Data](https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)
- **Total Rows**: 10,000
- **Total Features**: 17 (excluding the target variable and ID)
- **Target Variable**: `OUTCOME` (`1` indicates purchase, `0` indicates no purchase)

### Features:

- `AGE`: Age of the customer  
- `GENDER`: Gender of the customer  
- `DRIVING_EXPERIENCE`: Years of driving experience  
- `EDUCATION`: Education level  
- `INCOME`: Income level  
- `CREDIT_SCORE`: Credit score  
- `VEHICLE_YEAR`: Year of the vehicle  
- `VEHICLE_TYPE`: Type of vehicle  
- `ANNUAL_MILEAGE`: Annual mileage driven  
- `POSTAL_CODE`: Customer's postal code  
- `PAST_ACCIDENTS`: Number of past accidents  
- `OUTCOME`: Target variable indicating purchase (`1`) or not (`0`)

## 🧹 Data Preprocessing

- **Handling Missing Values**: Imputed missing values using appropriate strategies.
- **Encoding Categorical Variables**: Converted categorical variables into numerical format using one-hot encoding.
- **Feature Scaling**: Applied standardization to numerical features to normalize the data.

## 🔍 Feature Importance (Permutation)

Permutation importance was used to identify which features most influenced the model’s decision. The top contributing features included:
![feature_importance](https://github.com/user-attachments/assets/112fc058-4395-4a4d-b359-1c30e9c35040) <br>

1. `DRIVING_EXPERIENCE`
2. `VEHICLE_YEAR`
3. `POSTAL_CODE`
4. `GENDER`
5. `INCOME`
6. `AGE`
7. `ANNUAL_MILEAGE`
8. `CREDIT_SCORE`
9. `PAST_ACCIDENTS`
10. `EDUCATION`

## 📈 Exploratory Data Analysis (EDA)

### 📉 Visualization: Driving Experience vs. Target
![drivingexp_target](https://github.com/user-attachments/assets/0121beb4-6b05-4443-a58c-061a73b13dee) <br>

**Insight**: This bar chart illustrates the correlation between the number of years a customer has been driving and their likelihood of purchasing car insurance. It was observed that customers with less driving experience are more inclined to purchase insurance, possibly due to perceived higher risk.

📌 *Business Implication*: Focus marketing on less experienced drivers for higher conversion.
### 📉 Visualization: Vehicle Year vs. Target
![vehicleyear_target](https://github.com/user-attachments/assets/5bf88d0e-a8a8-47e1-bad9-6fb1331346ca) <br>

**Insight**: This line graph shows the relationship between the vehicle's manufacturing year and the insurance purchase rate. Customers owning older vehicles tend to purchase insurance more frequently, which may be attributed to concerns over potential repair costs.

📌 *Business Implication*: Target campaigns at owners of older vehicles.
## For Further Information
For any additional questions, please contact:
- Ali Abu Nimah 📧 [alibassab25@gmail.com](mailto:alibassab25@gmail.com)
