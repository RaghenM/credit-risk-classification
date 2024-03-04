# Credit Risk Report 
# Overview
The purpose of this analysis is to use a machine learning (supervised model) with a logistic regression to classify credit worthiness of folks applying for loans. A given classification of 0 is equal to "healthy loan", and a classification of 1 is equal to "high-risk loan". This model will help the bank 
to determine if a loan should be granted to the consumer/borrower that is applying. The dataset used to build this model is historical lending activity from a peer-to-peer lending services company. We use this data to both train and validate the model. A confusion matrix and classification report was used to determine the classification results. 

# Results 

   Confusion Matrix:

   
   <img width="232" alt="image" src="https://github.com/RaghenM/credit-risk-classification/assets/91345190/afc58925-5ee5-498d-ab29-8b7fa7e51b12">

   
    - 18655 true positive (occur when the model accurately predicts a positive data point.)
    - 36 false negative  (occur when the model mispredicts a negative data point.)
    - 110 false positive (occur when the model predicts a positive data point incorrectly)
    - 583 true negative (occur when the model accurately predicts a negative data point.)

1. Accuracy score: Precision is the Accuracy of positive predictions
2. Precision score: Precision is the Accuracy of positive predictions
3. Recall score: Recall is the ability of a classifier to find all positive instances.
   Classification Report:
<img width="474" alt="image" src="https://github.com/RaghenM/credit-risk-classification/assets/91345190/db24c3f8-1724-4344-973d-add1f15d0fed">



# Summary 
The model is almost perfect at predicting '0- healthy loans'. After reviewing the classification report, the 0 gets precision score of 1.00 and recall of .99 and an f1 of 1.00 which is the best score that can be assigned. The model also does well at predicting '1- high-risk loans'.
However, it does not do as well as the healthy loans. The scoring for the '1- high risk loans' is slightly lower at .84 for precision, .94 for recall, and .89 for the f1 score. Based on the scoring, I would categorize the model as good enough for both healthy and high-risk loan prediction.
