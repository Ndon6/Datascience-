Project title- Predictive-Modeling-for-Electric-Vehicle-Range-and-Efficiency.

Problem Statement- Accurately predicting the driving range and efficiency of electric vehicles (EVs) is a crucial challenge in the automotive industry. Range anxiety remains one of the biggest concerns for EV adoption, and understanding efficiency helps in optimizing powertrain design, charging infrastructure, and consumer confidence.
This project builds predictive models that estimate:
EV Range (km) → based on performance and powertrain features.
EV Efficiency (kWh/100km) → based on energy usage patterns.

Dataset Used- The dataset contains specifications of various electric vehicles, including:
Acceleration (0–100 km/h)
Top speed
Powertrain details
Battery capacity
Energy consumption
Other performance features
Note: Due to GitHub’s file size limits, the full dataset is not included. Please refer to the project documentation for dataset access.

Methods / Algorithms-
Data Preprocessing: Handling missing values, feature scaling, and transformations.
Exploratory Data Analysis (EDA): Identifying correlations between vehicle specs and range/efficiency.
Machine Learning Models:
Regression models for predicting range
Regression models for predicting efficiency
Evaluation Metrics: Mean Squared Error (MSE) and R-squared (R²).

Results-
Range Prediction
MSE: 10050.68
R²: 0.243 (low accuracy → model can be improved with feature engineering and advanced methods)
Efficiency Prediction
MSE: 21.41
R²: 0.981 (very high accuracy → strong predictive performance)
Plots & visualizations are included in the notebooks for better understanding of model behavior.

Future Improvements-
Range prediction can be Improve by using:
Feature engineering (aerodynamics, vehicle mass, weather conditions).
Advanced ML models (Gradient Boosting, XGBoost, or Neural Networks).
Deploying the best model as an interactive Streamlit dashboard.
Integrating real-world EV charging/usage data for higher accuracy.
Adding cross-validation and hyperparameter tuning.
