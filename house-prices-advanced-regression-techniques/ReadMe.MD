

---

# Homework 1 - House Prices Prediction

This project aims to predict house prices using data preprocessing, feature engineering, and linear regression. It is split into two parts: **Part 1** focuses on initial data processing and feature engineering, while **Part 2** completes the model training and testing pipeline.

---

## Part 1: Data Exploration and Preprocessing

### Steps:
1. **Data Loading**:
   - Loads training and test datasets for house prices.

2. **Exploratory Data Analysis**:
   - Plots histograms for dwelling type and house style.
   - Calculates summary statistics for missing values and single-category columns.

3. **Data Cleaning**:
   - Fills missing values with placeholders and normalizes numeric columns.
   - One-hot encodes categorical variables (e.g., street type).
   
4. **Feature Selection**:
   - Drops irrelevant features and encodes remaining categorical features as numeric.

5. **Matrix Preparation**:
   - Creates feature and target matrices (`X_train`, `y_train`) for model training.
   
6. **Linear Regression Model**:
   - Fits a linear regression model and evaluates it using Mean Squared Error (MSE) and \( R^2 \) score.

---

## Part 2: Model Training and Testing

### Steps:
1. **Data Cleaning and Encoding**:
   - Repeats cleaning and encoding steps on test data, handling missing values and scaling features to match the training set.

2. **Feature Scaling**:
   - Scales numerical features using Min-Max scaling.

3. **Model Training**:
   - Trains a linear regression model on the processed training data.

4. **Model Evaluation**:
   - Evaluates model performance using MSE and \( R^2 \) score on training data.

5. **Predictions and Submission**:
   - Makes predictions on test data, saving results in a CSV file for submission.

---

This project demonstrates a complete workflow for housing price prediction using linear regression, focusing on data preprocessing and feature engineering.
