# Module-12-Supervised-learning
Credit risk Classification
Imblalanced is the biggest challenge in credit risk classification. 
in this activity, I used various techniques to train and evaluate models with imbalanced classes by importing the following libraries:
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced
 
Split the Data into training and testing sets
Create a Logistic regression Model with Original Data
Predict a logisticRegression Model with the Resampled Training Data

Write a Credit Risk Report 

The logistic regression model prediction was great. 
The precision and recall score is averaged at 99 
The balanced accuracy score is 95

The logistic regression model fit with oversampled data was close to perfect.
The prediction is slightly higher than the not resampled model.
Both precision and recall score are 99
Accuracy score is 99 as well
