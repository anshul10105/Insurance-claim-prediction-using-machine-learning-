 **Background**

Insurance plays a crucial role in protecting individuals and organizations from financial uncertainty. One of the biggest challenges for insurance companies is claim management, as inaccurate estimation of claim amounts can lead to either financial losses or inefficient use of reserve capital.

Traditionally, insurers rely on manual analysis and rule-based systems, which may fail to capture complex relationships between customer characteristics and claim costs. With the availability of historical insurance data, machine learning techniques provide an effective way to analyze patterns and predict future claim amounts more accurately. This project explores how data-driven methods can support better financial planning and risk management in the insurance industry.

 **Problem Statement**

The insurance company is facing difficulty in estimating the amount of money required to settle future claims. Unexpected high-value claims can result in cash shortages and financial instability.

The goal of this project is to predict the insurance claim amount for each customer based on historical data, enabling the company to:

Plan reserve funds in advance

Reduce financial risk

Improve claim-related decision-making

**Dataset**

Source: Excel file

Based on the Medical Cost Personal Dataset

Features include:

Age- Age of Policyholders

Sex- Gender 

BMI- Body Mass Index

children-Number of dependants

Smoker-Smoking status

Target variable: Insurance charges- Insurance claim amount 

Problem type: Supervised Machine Learning – Regression

 **Methodology**
1️. **Data Exploration & Visualization**

Loaded and explored the dataset using Pandas

Performed exploratory data analysis (EDA) to understand data distribution

Visualized relationships between features and insurance charges.

Identified smoking status, age, and BMI as influential factors

2️. **Data Preprocessing**

Verified absence of missing values

Applied label encoding to categorical variables

Removed less impactful features

Applied standard scaling to normalize data

3️.**Feature Engineering**

Used Principal Component Analysis (PCA) during experimentation for feature extraction and dimensionality reduction but retained original feature due to better feature interpretability

4️. **Model Development**

Built a Random Forest Regression model to predict insurance claim amounts

Selected Random Forest due to its ability to model non-linear relationships

5️. **Model Evaluation**

Evaluated the model using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Achieved an R² score of ~0.85

6️. **Prediction on New Data**

Predicted insurance claim amounts for unseen customer inputs

 Results & Insights

The model demonstrated good predictive performance on test data

Smoking status significantly increased predicted claim amounts

The approach can assist insurers in reserve planning and financial forecasting

**Tools & Technologies**

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Excel, Jupyter Notebook

 **Key Learnings**

Framing a real-world insurance problem as a regression task

Importance of EDA and preprocessing in model accuracy

Practical application of Random Forest Regression

Understanding how ML supports risk and cost estimation
