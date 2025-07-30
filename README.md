# Online News Popularity Prediction using Machine Learning

This project use machine learning regression models to predict the popularity of online news articles based on their features such as content, metadata, and publication details.
# Project Objective
To build a predictive model that estimates the number of shares an article is likely to receive, helping media companies and marketers understand what drives news engagement.
# Machine Learning Models Used
- XGBoost Regressor
- Random Forest Regressor
- Linear Regression
# Data Preprocessing
- Removed outliers using IQR method
- Applied logarithmic transformation on the target variable (`shares`)
- Standardized features using `StandardScaler`
- Train-Test Split for model validation
# Model Evaluation
1. The performance of each model was evaluated using three standard regression metrics: R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
2. XGBoost Regressor achieved the highest R² score, indicating it explained the variance in the data better than the other models.
3. Random Forest Regressor also performed well, slightly behind XGBoost, and demonstrated its ability to handle complex patterns in the dataset.
4. Linear Regression, used as a baseline model, produced significantly lower accuracy, suggesting that the data has non-linear relationships that simple linear models couldn’t capture.
5. The comparison of the three models showed that ensemble-based methods, especially XGBoost, are more effective for predicting online content popularity.
# Visual Analysis
- Scatter plots: Actual vs Predicted
- Residuals Distribution
- Bar chart of model performance
# Conclusion
XGBoost Regressor outperformed other models with the highest R² score and lowest errors. This shows the effectiveness of ensemble-based models in capturing complex patterns in data.
