# 🚕 NYC Taxi Trip Duration Prediction
 
## 📌 Project Overview
 
This project focuses on building machine learning models to predict taxi trip duration in New York City based on trip characteristics and weather conditions.
 
Several machine learning approaches were evaluated, including Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and Polynomial Regression, in order to identify the most accurate model.
 
The main objective is to predict trip duration through data analysis, feature engineering, hyperparameter optimization, and model evaluation using industry-standard regression metrics.
 
---
 
## 🎯 Project Goals
 
- Analyze New York City taxi trip data
- Perform feature engineering and data preprocessing
- Integrate weather information into the dataset
- Train and compare multiple regression models
- Evaluate model performance using appropriate metrics
- Select the best-performing model
 
---
 
## 📊 Dataset
 
The project uses two datasets:
 
### NYC Taxi Trips Dataset
 
Contains:
 
- Trip duration
- Pickup coordinates
- Dropoff coordinates
- Passenger count
- Date and time information
 
### NYC Weather Dataset
 
Contains:
 
- Temperature
- Visibility
- Precipitation
- Weather conditions
- Additional meteorological features
 
---
 
## 📂 Features Used
 
- Pickup and dropoff locations
- Passenger count
- Time of day
- Day of week
- Weather conditions
- Engineered distance-based features
- Temporal features
 
---
 
## 📈 Evaluation Metrics
 
Model performance was assessed using:
 
### RMSLE
 
**Root Mean Squared Logarithmic Error**
 
Measures prediction accuracy while reducing the impact of large outliers.
 
### MedAE
 
**Median Absolute Error**
 
Measures the median absolute difference between predicted and actual values.
 
---
 
## 🤖 Machine Learning Models
 
The following models were trained and evaluated:
 
- Linear Regression
- Polynomial Regression (2nd Degree)
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
 
Each model was evaluated on training and validation datasets to achieve the lowest possible RMSLE and MedAE scores.
 
---
 
## 🛠 Technologies
 
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook
 
---
 
## 🚀 Installation
 
Clone the repository:
 
```bash
git clone https://github.com/Alex1988Den/Taxi-Trip-Duration-Prediction.git
cd Taxi-Trip-Duration-Prediction
```
 
Install dependencies:
 
```bash
pip install -r requirements.txt
```
 
Launch Jupyter Notebook:
 
```bash
jupyter notebook
```
 
---
 
## 📊 Key Techniques
 
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Hyperparameter Tuning
- Regression Modeling
- Model Evaluation
- Weather Data Integration
 
---
 
## 💡 Notes
 
- Weather information was incorporated to improve prediction accuracy.
- Hyperparameter optimization was performed for several models.
- Log-transformed target variables were used to improve prediction stability.
- Multiple regression algorithms were compared to identify the best-performing solution.
 
---
 
## 👨‍💻 Author
 
Developed by **Aleksandr Denissov**
 
📧 Email: aleksandr.denissov@brave.ee
 
---
 
⭐ If you find this project useful, feel free to leave a star on GitHub.
