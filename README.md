# **Credit Card Fraud Detection**
### - By *Shishir Agarwal*

The repository contains the Jupyter Notebook models.ipynb file that demonstrates the implementation of 4 different machine learning models on a dataset containing information about credit card transactions having 30 features, and one target value 'Class'
The models' main purpose is to predict if a Credit Card transaction is fraud or not, based upon the 30 attributes or features.
The 4 models are-
- Random Forest
- Logistic Regression
- Decision Trees
- Gradient Boosting Classifier

The accuracy and precision of all the models are compared and a bar graph is drawn to show how well an algorithm performs than others.

## **Data Set**
The data set is obtained from Kaggle-
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset creditcard.csv contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation.
Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. 

Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## **Dependencies**

The following libraries and tools are required for this project:
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- scikit-learn

## Usage

1. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```
2. Download the Dataset from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.
3. Open `models.ipynb` in the Jupyter interface.
4. Update the file path in the notebook at line 11 in data = pd.read_csv(*path*)
5. Run the cells in the notebook to see the analysis and results.
