# AP-MOLLER-AIML-ASSIGNMENT

## Project Overview
This project focuses on building predictive models to forecast the sourcing costs based on historical data. The goal is to utilize various regression techniques to predict monthly sourcing costs effectively, aiding in better financial planning and strategy development for supply chain management.

## Objective
The primary objective of this project is to:
- Develop a robust predictive model that can forecast the monthly sourcing costs with high accuracy.
- Compare different regression models to identify the most effective approach in terms of predictive performance and computational efficiency.
- Provide insights into the factors influencing sourcing costs, facilitating more informed decision-making processes.

## Data
The dataset used in this project includes historical sourcing data, which comprises several features such as product type, sourcing channel, and monthly sourcing costs. The data spans from July 2020 to May 2021, used for training the models, with June 2021 serving as the test set.

## Methodology
### Data Preprocessing
- **Data Cleaning**: Handle missing values and outliers to improve model accuracy.
- **Feature Engineering**: Extract useful features from existing data, such as transforming the 'Month of Sourcing' into a datetime object for time series analysis.
- **Data Splitting**: The dataset is split into training and test sets to evaluate model performance effectively.

### Model Development
Several regression models were explored in this project:
- **Linear Models**: Linear Regression, Lasso, Ridge.
- **Tree-based Models**: Decision Tree, Random Forest, Gradient Boosting, LightGBM, XGBoost.
- **Ensemble Methods**: Bagging with a Random Forest base model.
- **Neighbors-based Model**: K-Nearest Neighbors (KNN).
- **Support Vector Machine**: Using SVR with a linear kernel.

### Model Evaluation
Model performance was evaluated using the following metrics:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared

## Results
The Random Forest model outperformed other models, showing the lowest MSE and the highest R-squared value, indicating its superior capability in capturing the variability and complexity of the data.

## Conclusion
The findings from this project highlight the effectiveness of ensemble methods, particularly Random Forest, in handling complex datasets with non-linear relationships. Future work will focus on tuning the hyperparameters of the Random Forest model further and exploring hybrid models to enhance predictive accuracy.
