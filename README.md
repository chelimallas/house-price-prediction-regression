# house-price-prediction-regression

House Price Prediction - Machine Learning Lab

This repository showcases a machine learning project aimed at predicting house prices using regression models. The work includes essential steps such as data preprocessing, exploratory data analysis (EDA), model development, and performance evaluation. All code and results are documented in a Jupyter notebook and summarized in a final report.

Objective

The main goal of this lab is to explore how regression techniques can be used to predict house prices based on various features. Through this project, we aim to understand the influence of different variables on price and evaluate which machine learning model performs best in this context.

Data Preprocessing

The dataset was first cleaned to handle missing values effectively. Categorical variables were encoded using label encoding, and numerical features were standardized to ensure model stability and comparability. To better understand the structure and characteristics of the data, we performed exploratory data analysis (EDA), which included visualizations like histograms, boxplots, and correlation heatmaps. These steps helped identify important features that influence house prices and informed model selection.

Model Development

Two regression models were implemented for this project: Linear Regression and Ridge Regression. Both models were trained using the cleaned and transformed dataset. We then used these models to make predictions on house prices. The use of different models allowed us to compare how well each could capture the underlying patterns in the data.

Model Evaluation

To assess model performance, we calculated key evaluation metrics including Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). These metrics helped us compare the accuracy of the two models. A discussion is provided in the report to explain why one model performed better than the other based on the data and evaluation results.

Requirements

To run this project, you will need Python 3 and several Python libraries including `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`. You can install these dependencies using the following command:

```bash
pip install -r requirements.txt
```

