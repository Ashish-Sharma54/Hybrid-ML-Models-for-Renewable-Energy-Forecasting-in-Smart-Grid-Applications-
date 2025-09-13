# Hybrid-ML-Models-for-Renewable-Energy-Forecasting-in-Smart-Grid-Applications-
Hybrid-RECast: Smart Renewable Energy Forecasting
📌 Overview
Hybrid-RECast is a hybrid machine learning model designed to accurately forecast renewable energy outputs based on environmental factors like temperature, pressure, light intensity, UV index, and humidity.
Our solution combines LightGBM, XGBoost, and Linear Regression in a stacking ensemble, resulting in a robust and reliable prediction pipeline.

🎯 Inspiration
Energy forecasting is a critical challenge in the transition towards sustainable energy systems.
We were inspired by the idea of improving renewable energy utilization by making predictions more accurate, which helps in reducing energy waste and improving grid stability.

🚀 Features
📊 Hybrid ML Model: Combines multiple algorithms for improved accuracy
🧹 Smart Preprocessing: Handles missing data, feature selection, and encoding automatically
📈 High Accuracy: Optimized for lower MAE and RMSE
🔗 Extensible: Can be integrated with IoT systems for real-time forecasting
🏗 How We Built It

Data Preprocessing:
Handled missing data using SimpleImputer
Converted continuous variables to categories for better interpretability
Performed Chi-Square test for feature selection

Modeling:
Built a Stacking Regressor with LightGBM, XGBoost, and Linear Regression
Tuned hyperparameters for optimal performance

Evaluation:
Used MAE, MSE, RMSE, and R² Score for evaluation

💡 Tech Stack
Languages: Python
Libraries: Pandas, NumPy, Scikit-learn, LightGBM, XGBoost
Techniques: Stacking Regressor, Chi-Square Feature Selection, Missing Value Imputation
Version Control: Git, GitHub
Environment: Google Collab


🏆 Challenges We Faced
Handling noisy and incomplete dataset
Balancing bias-variance tradeoff in hybrid models
Achieving lower MAE while keeping model complexity low

🎓 What We Learned
Importance of feature selection in improving ML model performance
How stacking models can outperform single models
How to design a robust ML pipeline from data preprocessing → model training → evaluation

🔮 What's Next
Integrate with IoT-based energy meters for real-time forecasting
Deploy using Streamlit or Flask for an interactive dashboard
Add deep learning models (like LSTM) for time-series forecasting
