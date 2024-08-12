# Credit Card Fraud Detection

This project implements a machine learning model to detect fraudulent credit card transactions.

## Dataset

The dataset used in this project is the Credit Card Fraud Detection dataset, which contains transactions made by credit cards in September 2013 by European cardholders.


## Libraries Used

- numpy
- pandas
- scikit-learn

## ACTION TAKES

1. Data Preprocessing:
   - Loaded the dataset using pandas
   - Checked for missing values (none found)
   - Analyzed the distribution of legitimate vs fraudulent transactions

2. Handling Imbalanced Data:
   - Used undersampling technique to balance the dataset
   - Created a new balanced dataset with equal number of legitimate and fraudulent transactions

3. Model Training:
   - Split the data into training (80%) and testing (20%) sets
   - Used Logistic Regression as the classification model

4. Model Evaluation:
   - Evaluated the model using accuracy score on both training and test data

## Results

- Accuracy on training data: 94.03%
- Accuracy on test data: 94.42%

