Project Walkthrough




Notebook #1 - Data Pre-processing

In this notebook, the data was loaded and cleaned. First, nulls and duplicates were taken care of, then each of the categorical columns was refined. Some of the categorical columns had to be decoded using standard hospital encoding systems such as the ICD 9. 

The distribution of data in each category was also checked in this notebook. The cleaned datasets were exported as CSV files to be used in the subsequent notebooks.



Notebook #2 - Modelling

In this notebook, the data the clean datasets exported from notebook 1 were modeled with Logistic Regression, Decision Tree, AdaBoost, and K Nearest Neighbors.



Notebook #3 - Advanced Modelling

In this notebook, the second subset of dataset 1 was modeled using Keras Sequential Model, in an effort to improve its accuracy score.



Notebook #4 - Model Deployment

Lastly, this notebook was used to make a pickle file of the Logistic model of dataset 2. The pickle file of the model was then exported and deployed using a flask app and Heroku. 







