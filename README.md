# Uncovering-Health-Patterns-and-Risk-Factors-An-Analytical-Study-of-BRFSS-using-R

## Overview

This project develops a predictive disease model using machine learning to improve health insurance management. The model predicts the likelihood of diseases based on patient data, aiding insurance companies in optimizing plans and enhancing customer service.

### Libraries Used:
`readr`, `dplyr`, `tidyverse`, `janitor`, `tidyr`, `lubridate`, `skimr`, `ggplot2`, `corrplot`, `DataExplorer`, `stats`, `psych`, `broom`, `caret`, `randomForest`, `e1071`, `xgboost`, `glmnet`, `pROC
`
## Methods

1. **Data Preprocessing**:
   - Importing and cleaning data.
   - Handling missing values and feature engineering.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing data distributions and relationships.
   - Identifying patterns and anomalies.

3. **Statistical Analysis**:
   - Conducting statistical tests to identify significant features.
   - Analyzing feature correlations.

4. **Machine Learning Models**:
   - Implementing algorithms like Logistic Regression, Decision Trees, and Random Forests.
   - Training and evaluating models using cross-validation.
   - Hyperparameter tuning.

5. **Model Interpretation with SHAP**:
   - Calculating SHAP values to understand feature importance.
   - Visualizing SHAP values for model interpretation.

## Structure

1. **Introduction**: Project objectives and dataset description.
2. **Data Preprocessing**: Loading and cleaning data.
3. **EDA**: Visualizing and analyzing data.
4. **Statistical Analysis**: Correlation and significance testing.
5. **Machine Learning**: Model training, evaluation, and tuning.
6. 
## Results and Insights

The analysis provides insights into disease prediction factors. Statistical analysis identifies significant features, while SHAP values explain model predictions, enhancing interpretability and trustworthiness.

## Conclusion

This project showcases the use of statistical analysis, machine learning, for disease prediction and effective health insurance management. The techniques are applicable to other domains requiring model interpretabilit.
The best model accuracy achieved is 84.3% using the Random Forest with upscaled Boruta features. The highest
True Positive Rate is 0.7903 and True Negative Rate is 0.8796, both achieved by the KNN model with upscaled CFS
features. A total of 36 models were evaluated to find the most effective method. 
