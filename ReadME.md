# TikTok Claim Classification Project

![TikTok Logo](OIP.jpg)

This repository contains code for analyzing and modeling TikTok data. The script covers various aspects, including data inspection, analysis, exploratory data analysis (EDA), hypothesis testing, regression modeling, and model evaluation.

## Overview

This project involves the analysis of a TikTok dataset with a focus on data exploration, statistical analysis, data modeling, and hypothesis testing. The primary goal is to gain insights into various aspects of the dataset, such as video characteristics, engagement metrics, and the relationship between different variables.


## Table of Contents
## Table of Contents
- [Inspection and Analysis](#inspection-and-analysis)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Exploration and Hypothesis Testing](#data-exploration-and-hypothesis-testing)
- [Regression Modeling](#regression-modeling)
- [Classifying Videos Using Machine Learning](#classifying-videos-using-machine-learning)

## Project Structure

1. **Data Inspection and Analysis:**
   - **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scipy
   - **Objective:** Load the dataset, explore basic statistics, and analyze key features such as claim status, author ban status, and engagement metrics.

2. **Exploratory Data Analysis (EDA):**
   - **Libraries Used:** Seaborn, Matplotlib
   - **Objective:** Visualize the distribution of data, explore relationships between variables, and identify patterns or trends.

3. **Hypothesis Testing:**
   - **Libraries Used:** Scipy
   - **Objective:** Conduct hypothesis testing to validate or refute assumptions about the dataset. For example, testing if there's a significant difference in mean video view count between verified and unverified accounts.

4. **Regression Modeling:**
   - **Libraries Used:** Scikit-learn
   - **Objective:** Build a logistic regression model to predict the 'verified_status' based on various features. Includes data preprocessing, encoding, model training, and evaluation.

5. **Random Forest and XGBoost Models:**
   - **Libraries Used:** Scikit-learn, XGBoost
   - **Objective:** Build and evaluate Random Forest and XGBoost models for predicting the 'claim_status' based on different features.

6. **Feature Engineering:**
   - **Libraries Used:** Scikit-learn
   - **Objective:** Create additional features, such as text length, and explore their impact on the models.

7. **Model Evaluation:**
   - **Objective:** Evaluate the performance of models using metrics like accuracy, precision, recall, and F1-score. Compare models and identify the most effective one.

8. **Visualization:**
   - **Libraries Used:** Seaborn, Matplotlib
   - **Objective:** Visualize key insights, distributions, and relationships identified during the analysis.

## Instructions for Running the Code

1. **Run the Jupyter Notebook:**
   - Execute the Jupyter Notebook sequentially to run the code cells and observe the analysis.

2. **Interpret Results:**
   - Review the generated visualizations, statistical analyses, and model performance metrics to draw conclusions about the dataset.

3. **Modify and Experiment:**
   - Feel free to modify parameters, features, or conduct additional analyses to further explore the dataset.

## Conclusion

This project provides a comprehensive analysis of the TikTok dataset, covering various aspects from data exploration to advanced modeling. The results and insights gained can inform decision-making processes and contribute to a deeper understanding of the dataset.

...
