# Wine-Quality-Prediction using Machine Learning
This project focuses on predicting the quality of wine (good or bad) based on its physicochemical properties such as acidity, sugar, pH, alcohol content, etc.The dataset comes from the UCI Machine Learning Repository and is widely used for classification tasks in ML. The main goal is to build a machine learning model that can classify wine as good quality (score ≥ 7) or bad quality (score < 7).Dataset

# Dataset
The dataset contains two CSV files:
- Red wine data → winequality-red.csv
- White wine data → winequality-white.csv
Each record includes 11 input features (numeric) and 1 output column (quality).
The 11 input features are
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
FINALLY THE TARGET : quality (score between 0 and 10)

# Project Workflow
STEP 1 : Data Collection
- Download dataset from UCI Repository
- Load into pandas DataFrame.
  
STEP 2 : Exploratory Data Analysis (EDA)
- Check for null values
- Visualize correlations between features and wine quality
- Understand distribution of target variable

STEP 3 : Data Preprocessing
- Convert wine quality into binary classification:
  .Good (≥ 7) → 1
  .Bad (< 7) → 0
- Train-test split

STEP 4 : Model Building
- Logistic Regression (baseline model)
- Other models (optional: Random Forest, SVM, XGBoost)

STEP 5 : Model Evaluation
- Accuracy Score
- Confusion Matrix
-Classification Report

# Results
- Logistic Regression achieved around 75% accuracy on the test dataset.
- Alcohol content, sulphates, and volatile acidity were strong predictors of wine quality.

# Tech Stack
- Python
- Pandas & NumPy for data handling
- Matplotlib & Seaborn for data visualization
- Scikit-learn for ML models & evaluation

# What You’ll Learn
By going through this project, you will learn:
✅ How to load and explore real-world datasets in Pandas
✅ How to clean, preprocess, and prepare data for machine learning
✅ How to perform exploratory data analysis (EDA) with Matplotlib & Seaborn
✅ How to convert a regression dataset into a binary classification problem
✅ How to build and train a Logistic Regression model using Scikit-learn
✅ How to evaluate models using accuracy, confusion matrix, and classification report
✅ How to structure a project for Google Colab & GitHub
✅ How to write a clean and professional README for ML projects
