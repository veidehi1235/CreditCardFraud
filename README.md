# CreditCardFraud

## Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## __Plan of Action__ - 
structure and Plan the Methodology to go about solving this problem - 

- Understading the Data , Exploring it's length , breadth and height ( How BIG , How DIVERSE , How GRANULAR )   Called : __EDA__

- __Visualisation of Data for Finding any specific Pattern or Flaw in the Data that can effect the Model__

- Finding the Complexities and Roadblocks for Modelling this particular Use Case

- Solving Use Case Specific Problems and consequently Handling Errors , Outliers and Missing Values in the Data

- Processing and Cleaning the Data to make it fit for Modelling and feeding to a Machine Learning Model

- Splitting the Dataset into Training and Testing Datasets

- Training the data on Multiple Classification Models

- Evaluating Models based on various Metrics and Understanding which metric is the most appropriate for Model Evaluation

- further ways to improve the model , feedback mechanism for the model and saving the model for future use
