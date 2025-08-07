# Predicting-Absolute-Humidity

<img width="860" height="480" alt="image" src="https://github.com/user-attachments/assets/10936dc7-75a6-4636-88ba-8bcd564a3bc9" />


# INTRODUCTION

This project focuses on predicting absolute humidity using air quality sensor data. By applying regression models like Linear Regression, Random Forest, and SVR, the aim was to identify key environmental features and build an accurate predictive model. The data comes from the UCI Air Quality dataset.

# TECHNOLOGIES USED

- Python

- Pandas, Numpy

- Scikit learn

- Matplotlib, Seaborn

# MODELLING APPROACH

- Loaded and cleaned real-world air quality data.

- Performed feature selection using Recursive Feature Elimination (RFE).

- Trained three regression models:

  - Linear Regression

  - Random Forest Regressor

  - Support Vector Regressor (SVR)

- Evaluated model performance using RMSE (Root Mean Squared Error).

  # RESULTS

- **Best model**: Random Forest Regressor

- **Top features**: Temperature, CO(GT), NOx(GT), Relative Humidity

# Real-World Use Cases of Absolute Humidity Prediction

- 🏥 **Healthcare & Infection Control**  
  Absolute humidity directly affects virus survival and transmission. Hospitals can use predictive systems like this to maintain optimal indoor environments to reduce the spread of infections like the flu or COVID-19.

- 🏭 **Smart HVAC & Energy Optimization**  
  HVAC systems use humidity predictions to efficiently regulate indoor climate, reducing energy consumption in commercial and residential buildings.

- 🌱 **Agriculture & Greenhouse Management**  
  In controlled farming envi
