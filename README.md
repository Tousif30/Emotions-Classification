# Emotions-Classification
## Overview
This project involves the classification of emotions according to the specific text. The data for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp).
## Methodology
Firstly the texts were cleaned by the utilization of the regular expression library and the texts were processed via the NLTK library. Moving on three machine learning models were created: Logistic Regression, Support Vector Classifier and Multinomial Naive Bayes classifier. Then hyperparameter tuning was conducted to determined the best parameters to improve the accuracy of the models.
## Conclusion
Overall, the tuned Logistic Regression model produced the highest accuracy of 0.902. The labels "sadness" and "joy" had individual precision scores of more than 0.90 as there were significantly more training and testing data for these labels.
