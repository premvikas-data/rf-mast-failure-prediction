# RF Mast Failure Prediction 📡

This project develops a machine learning model to predict the susceptibility of RF radio masts to weather-induced failures. Using Gradient Boosting with hyperparameter tuning and cost-sensitive analysis, we provide a framework to improve operational resilience in telecom infrastructure.

## Key Highlights
- Full data preprocessing (EDA, feature engineering, correlation handling)
- Machine Learning models: Random Forest, Logistic Regression, Gradient Boosting
- Hyperparameter tuning using Grid Search CV
- Cost-sensitive modeling for real-world deployment scenarios (cost ratios 1:5, 1:10, 1:20)
- Final prediction deployment on unseen scoring dataset

## Technologies Used
- Python (Pandas, Scikit-Learn, Matplotlib)
- Jupyter Notebook
- Cost-sensitive classification
- Feature importance extraction and visualization

## Data Overview
- 2186 records for training across 79 attributes
- 936 records in scoring dataset
- Source: Simulated RF mast data for telecom service reliability prediction

## Future Enhancements
- Integrating real-time weather and location data
- Continuous model refinement with live feedback
- Expansion to broader telecom infrastructure risk analytics

## Author
Prem Vikas
