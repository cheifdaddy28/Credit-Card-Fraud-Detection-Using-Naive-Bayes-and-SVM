# Credit-Card-Fraud-Detection-Using-Naive-Bayes-and-SVM
MSc Data Science Thesis 


# Motivation
Credit Card Fraud as indicated in the background is a very major issue which has significant consequence on global economy. Credit card affects several stakeholders in the economy. The public who patronise the card, the finance institution, regulators and the government. Therefore, the issue of great priority to all these stakeholder groups. People are really concerned about the rate of credit card fraud incidents. Stakeholders are concerned about the issue and are in support of measures that need to be instigated in other to insulate the sector against such attacks. 

# Project Objectives
1.	To predict whether a credit card is being used by the cardholder or a fraudster using machine learning algorithms
2.	To distinguish between authentic and fraudulent credit card transaction
3.	To create a fraud detector application

# Research Questions
1.	How will machine learning algorithm be used in detecting detect credit card fraud?
2.	How to identify and distinguish between fraudulent and credit authentic credit card transaction?


# Results and Implementation

The web development is done in two parts:

Cc.py: This file contains the code that defines the user interface and interacts with the machine learning model. It uses the Python library Streamlit to create an interactive interface that allows users to input credit card information and make predictions. The interface includes input fields for the type of transaction, the amount, and the original and destination account balances. It also includes two buttons: one to submit the input information for a prediction and another to generate random values for the input fields.

engine.py: This file contains the code for the machine learning model. It imports the model and PCA object from a pickle file and defines the makePcaPred and makeRand functions. The makePcaPred function takes in the user's input information, applies PCA dimensionality reduction to it, and then uses the machine learning model to make a prediction. The makeRand function generates random numbers for input values for the interface


# On Model Performance

In summary, based on the results, the SVM model seems to be performing better on this dataset compared to the naive Bayes model. The SVM model has a higher precision, recall, and F1 score, as well as a higher ROC AUC score, indicating that it is better at distinguishing between the positive and negative cases in the dataset.

# Conclusion 
The models performance well in all the models. The model proved efficient in predicting credit card fraud. Implementation of the model was via the development of a website. The web development methodology for the credit card fraud detection project involves the use of the Streamlit library to create an interactive interface for users to input credit card information and the use of the PCA object and machine learning model to make predictions about whether or not the transaction is fraudulent. 


