# Cancer-Identification-Logistic-Regression
Probability of Cancer being benign or malignant using Logisitic Regression. Coded in Python using Jupyter Notebook.

Used pandas and seaborn packages to complete.

Cancer dataset pulled from Kaggle
Breast Cancer Wisconsin (Diagnostic) Data Set
  Website states the dataset is used to predict whether the cancer is benign or malignant.

The following steps were performed:
1. Exploratory Data Analysis

2. Data Cleaning:
   
  A. Dropped 2 columns that were not useful for analysis. Unamed"32 and id columns dropped
  
  B. Changed diagnosis to M(Malignant) to 1 and B(Benign) to 0 which made it int64 data type and usable for Logistic Regression.

4. Divided data into target variable (diagnosis) and predictors (remaining columns).

5. Created a scaler object

6. Fit scaler to the data and transformed the data

7. Split the data into a train and test split

8. Trained the Logistic Regresion model

9. Evaluate the model
    
  A. Model had an accuracy of 0.98 or 98%
