# Explainable-AI-Project

## Abstract

In credit card fraud detection problem, we are trying to tackle two problems- one is to eradicate the data imbalance between fraud and genuine transactions and the other is to provide interpretation of a black box model’s output to predict the possibility of fraud transactions. To tackle the data imbalance, two feature engineering approaches were tried namely SMOTE and random under sampling. Results of SMOTE were better as compared to under sampling and hence it was used to balance the fraud transaction data with the genuine transaction data. Various Machine Learning models namely SVM, Decision Tree, Logistic Regression and KNN were used to build a prediction system. Along with these ML algorithms, a Deep Neural Network (DNN) was also trained on the data and used for prediction. From the precision-recall curve and ROC-AUC curve comparison we found that Deep Neural Network performed better as compared to the other Machine Learning models. Since DNN is a black box system it becomes important to understand the explanibility of the system as we need to know why the decision was made along with the actual decision. To attain that, we have two white box explainers LIME and SHAP added to the top of our DNN model to better understand the outputs of our prediction. Prediction analyses by two explainers are presented, providing a clear picture of how each attribute of an interest instance contributes to the final model output. 

- Refer to the pdf XAI_Project_Paper.pdf for the complete detials about the project
- Refer to the file Credit_Card_Fraud_Detection_New-2.ipynb for the coding notebook

## Authors
Ajinkya Pawale (ajpawale@iu.edu)
Abhishek Sharma (absharm@iu.edu) 
