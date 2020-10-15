# Titanic_journey
This is my first problem at Kaggle. I chose the Titanic competition which is a good way to introduce feature engineering and ensemble modeling. Firstly, I will focus on the feature engineering. Last part concerns modeling and predicting the survival on the Titanic.

This script follows three main parts:
Feature analysis
Feature engineering
Modeling

1. Perform Exploratory Analysis: It is important to deploy descriptive and graphical statistics to look for potential problems, patterns, classifications, correlations and comparisons in the dataset.

2. Prepare Data for Consumption: This step is often referred to as data wrangling, a required process to turn “wild” data into “manageable” data. This includes data cleaning to identify aberrant, missing, or outlier data points. We change our features based on our assumptions and findings. We will be dropping some variables, creating new ones from existing, converting categorical features(using sklearn OneHotEncoder, labelEncoder and pandas get_dummies) and completing missing variables. The completion goal achieves desired requirement for model algorithm to operate on non-null values.

3. Model Data: Our problem is a classification problem. We want to identify relationship between output (Survived or not) with other variables or features. We must understand the type of problem and solution requirement to narrow down to a select few models which we can evaluate. The wrong model can lead to poor performance at best and the wrong conclusion at worst.

4. Validate and Optimize Data Model: Hyperparameter tunning for best models. We performed a GRID SEARCH optimization for RandomForest, GradientBoosting and SVC classifiers.
