# Heart-Abnormality-Prediction
Analysis of MAX3010X Sensor Data Using Logistic Regression Model

Problem Statement:
To address the issue of detecting heart problems early on and providing timely
interventions, this project aims to develop a smart health monitoring system using
the ESP8266 and MAX3010X sensors. The goal is to create an accessible and cost-
effective solution that can monitor vital signs in real-time and classify individuals
as having heart problems or not using a logistic regression algorithm. By doing
so, individuals can monitor their health remotely and healthcare professionals can
receive valuable insights for better patient care. This solution can be especially
beneficial for individuals who have limited access to healthcare services or live in
remote areas.

Methodology:

![image](https://github.com/2001Sgouda/Heart-Abnormality-Prediction/assets/89405366/e724b18a-c4d7-4566-af0b-6a76abe5d8d8)

Circuit Connection and Blynk Interfacing

![image](https://github.com/2001Sgouda/Heart-Abnormality-Prediction/assets/89405366/9647e24c-4f60-48eb-8f72-cea38ef47624)

Logistic Regression Model:

Logistic regression is a type of machine learning algorithm that is commonly used for binary classification problems, where the goal is to predict whether an outcome is one of two possible values (e.g. yes or no, true or false, normal or abnormal).

![image](https://github.com/2001Sgouda/Heart-Abnormality-Prediction/assets/89405366/211ad00f-3244-477f-9f10-fa335a997737)

Using the Logistic Regression Model, we will calculate Precision, Recall and F1 score which are important for testing the accuracy of model.

Confusion Matrix:

Confusion matrix helps us to evaluate the performance of a model by comparing
its predicted values with the actual values. From the confusion  matrix we can calculate Precision, Recall and F1 score.

![image](https://github.com/2001Sgouda/Heart-Abnormality-Prediction/assets/89405366/ef9c50ff-5831-4b0b-b99d-85c448cca0ee)

Recall (R) =TP/(TP+FN).
High recall value: Model is good at identifying positive cases.

Precision (P)=TP/(TP+FP).
High precision value: Model is good at avoiding false positives.

F1 Score = 2PR/(P+R).
F1 score takes into account both precision and recall, and is a useful metric for evaluating the overall performance of a model.

ROC Curve:

Plot between TPR and FPR..A good model will have a curve that is closer to the top left corner, indicating higher TPR and lower FPR.

Correlation Matrix:

Plot describing the relationship among  datas in our datasheet.
Correlation Coefficient Range: -1 to 1
-1 indicates a perfect negative correlation (inverse proportional) 
0 indicates no correlation
1 indicates a perfect positive correlation (proportional).



