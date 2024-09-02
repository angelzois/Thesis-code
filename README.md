# Prediction Using Social Features Influence in C2C E-Commerce
This repository contains the code and materials for the thesis titled "Prediction Using Social Features Influence in C2C E-Commerce" by Angelos Zois. The thesis was submitted in partial fulfillment of the requirements for the degree of Master of Science in Data Science & Society at Tilburg University.

## Abstract
This thesis explores the impact of social features on predicting the number of products sold in a Consumer-to-Consumer (C2C) environment using machine learning techniques. It utilizes a dataset from a French C2C fashion e-commerce platform and applies Random Forest Regressor and XGBoost models. The study demonstrates that incorporating social features significantly enhances predictive performance.

## Methodology
The methodology involves several key steps:

### Data Preprocessing: 
Includes handling missing values, encoding categorical variables, and splitting the dataset.
### Model Training: 
Random Forest Regressor and XGBoost models are trained on the dataset with and without social features.
### Evaluation: 
The models are evaluated based on Mean Absolute Error (MAE). The study also explores the effect of applying the SMOTER technique to address data imbalance.
### Feature Importance Analysis: 
SHAP values are used to assess the importance of features in predicting sales.

For detailed steps, please refer to the [thesis_code.ipynb notebook](https://github.com/angelzois/Thesis-code/blob/main/thesis_code.ipynb).

## Results
The thesis found that social features such as the number of followers significantly improve the accuracy of sales predictions in C2C e-commerce platforms. Random Forest Regressor was identified as the best-performing model with a Mean Absolute Error of 0.0671.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


