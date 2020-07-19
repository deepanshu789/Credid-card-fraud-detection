# Credit-card-fraud-detection

# Objective: -

    In this project I have made a ml model which predict if a transaction is fraud or not.
    
# Dependencies:-
    1.NumPy
    2.Pandas
    3.SciKit-Learn
    4.Seaborn
    5.Matplotlib
# Dataset

   The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

   It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features and more background information about the data is not provided. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
    
    
# Detail: -
    
    Steps: -
      Data Handling

        1.Importing Data with Pandas
      
      Data Analysis
        1.Supervised Machine learning Techniques
        2. KNeighborsClassifier
        
      Valuation of the Analysis
        1.K-folds cross validation to valuate results.
        
# Results: -
    I used KNeighbors and got a accuracy of 99.8%. 
