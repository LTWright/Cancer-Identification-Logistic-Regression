# Cancer-Identification-Logistic-Regression
Probability of Cancer being benign or malignant using Logisitic Regression. Coded in Python using Jupyter Notebook.

Used pandas, seaborn packages to complete.

The following steps were performed:
1. Exploratory Data Analysis

2. Data Cleaning: 
  A. Dropped 2 columns that were not useful for analysis. Unamed"32 and id columns dropped
  B. Changed diagnosis to M(Malignant) to 1 and B(Benign) to 0 which made it int64 data type and usable for Logistic Regression.

3. Divided data into target variable (diagnosis) and predictors (remaining columns).

4. Created a scaler object

5. Fit scaler to the data and transformed the data

6. Split the data into a train test split

7. trained the Logistic Regresion model

8. Evalutate the model
   A. Model had an accuracy of 0.98 or 98%
