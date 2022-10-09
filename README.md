# Prediction-of-potential-Asset-Customers

### Business Objective

Bank has a growing customer base where the majority of them are liability customers (depositors) vs. borrowers (asset customers). The bank is interested in expanding the borrower’s base rapidly to bring in more business via loan interests.

As a data scientist, we have been assigned with a task to develop a machine learning model to identify potential borrowers from our existing liability customer base to support focused marketing.

 
### Data Description 

The dataset has 2 CSV files,

Data1 - 5000 rows and 8 columns
Data 2 - 5000 rows and 7 columns
 

### Aim

Build a machine learning model to perform focused digital marketing by predicting the potential customers who will convert from liability customers to asset customers.

 
### Tech stack

Language - Python
Libraries – numpy, pandas, matplotlib, seaborn, sklearn, pickle, imblearn
 

### Approach

1. Importing the required libraries and reading the dataset.
    Merging of the two datasets
    Understanding the dataset

2. Exploratory Data Analysis (EDA) –
    Data Visualization

3. Feature Engineering
    Dropping of unwanted columns
    Removal of null values
    Checking for multi-collinearity and removal of highly correlated features

4. Model Building
    Performing train test split
    Logistic Regression Model
    Weighted Logistic Regression Model
    Naive Bayes Model
    Support Vector Machine Model
    Decision Tree Classifier
    Random Forest Classifier

5. Model Validation
    Accuracy score
    Confusion matrix
    Area Under Curve (AUC)
    Recall score
    Precision score
    F1-score

6. Handling the unbalanced data using imblearn.

7. Hyperparameter Tuning (GridSearchCV)
    For Support Vector Machine Model

8. Creating the final model and making predictions
9. Save the model with the highest accuracy in the form of a pickle file.
