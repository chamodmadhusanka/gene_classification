# Leukemia Classification Model

This repository contains code for building and evaluating a classification model to predict the type of Leukemia as Acute Myeloid Leukemia (AML) or Acute Lymphoblastic Leukemia (ALL). 
The classifier aims to be interpretable, allowing users to understand how it identifies different classes. Interpretability is achieved through the use of rule-based classifiers, logistic regression, or decision trees.

## Dataset
The dataset has been pre-processed and divided into training and testing sets. Normalization has been applied to ensure consistent scaling across features.

## Model Building
Various classification algorithms, including rule-based classifiers, logistic regression, and decision trees, have been implemented and tuned to achieve the best possible prediction results. Model parameters have been optimized using the training set while avoiding the use of the test set for tuning.

## Evaluation
Model performance is evaluated using the testing set to assess its accuracy, precision, recall, and other relevant metrics. Additionally, explainable AI methods may be applied as a separate step to interpret the results of more complex models.
