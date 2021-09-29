# Anti Money Laundering Machine Learning & Deep Learning

This repository contains 2 Machine Learning & 1 Deep Learning Model to implement money laundering fraud detection. We have used Logistic Regression, Decision Tree and Graphical Neural Network (Node classification and Graph Classification) Models in the case study. Additionally we have also implemented Rule based model which will always check for certain rules before passing the data to any of the models and raise an suspicious alert on the particular accounts. In this project we have created a synthetic bank transaction data, which represents various fraud and non-fraud patterns of bank transactions. In the end our model predicts, whether the transaction is Fraud or Non-Fraud.

## Contents of the file

- The Input file 'data.json' given to cleaning pipeline for processing the data is stored inside Input folder.
```
Input/transactions.csv
Input/accounts.csv
```

- The final fraud transaction and accounts highlighted csv file 'Fraud-transaction.csv' is stored inside Output folder
```
Output/Fraud-transaction.csv
```
- All the machine learning and deep learning models are stored inside Models folder.
```
Model/logistic_regression.py
Model/decision_tree.py
Model/graphical_neural_network.py
Model/rule_based.py
```
- The document consisting of model research is stored inside Document folder.
```
Document/manuscript.pdf
```
- To install Python packages with pip and requirements.txt
```
requirements.txt
```

## Pipeline for Logistic regression, decision tree and graphical neural networks model is as follows :

![alt text](https://github.com/KirtiRasal/Instaffo-Job-Title-Classification-Project/blob/main/Images/cleaning%20pipeline%20image.png?raw=true)

## Environment

We need a python environment for executing the models. Latest python version (3.9.6) for 64 bit Windows 10 can be supportive to run these files.

## Installation

pip version 21.1.3

Install packages with pip: -r requirements.txt

The following command will install the packages according to the configuration file requirements.txt. 
Run the following command where requirements.txt file is located.
```
pip install -r requirements.txt
```

Description of the python packages used in the text cleaning pipeline.

1. pandas is used to read the input json file.

2. pytorch

3. 

4.

5. 

## Execution

Change the directory of the file where project is located.

Firstly, run the Model/logistic_regression.py python file using below command

``` python Cleaning_Pipeline_Task_1/text_classification.py ```

Secondly, run the Model/logistic_regression.py python file using below command

``` python Cleaning_Pipeline_Task_1/text_classification.py ```

Run the Model/logistic_regression.py python file using below command

``` python Cleaning_Pipeline_Task_1/text_classification.py ```

After the command is executed, output will be stored in ``` Output/Fraud-transaction.csv ``` location


