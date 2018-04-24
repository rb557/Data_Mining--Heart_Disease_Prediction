# Data_Mining--Heart_Disease_Prediction


So this project was taken from http://archive.ics.uci.edu/ml/datasets/Heart+Disease


Since I took the unprocessed data first. So, I started filtering out the unwanted data set and normalized the existing one. I changed the some values like '?' and deleted them and changed the integer value to the floating value to get the clear accuracy. But the accuracy rate for the unprocessed data set was not linear and so I went ahead with the processed data set.


In processed data set based on the 3 classifiers which are
1. Logistic Regression
2. Random Forest
3. Gradient Boosting
I calculated the accuracy, precision,recall and F1 meaure.
With the different classifiers I came up with the conclusion that Random Forest was the best to predict Heart Disease and Gradient Boosting was close to it based on Precision,Recall and F1 measure. I didn't consider the Accuracy while predicting Heart Disease becacuse of the Accuracy Paradox.


Question. What is Accuracy Paradox?
Answer: The accuracy paradox for predictive analytics states that predictive models with a given level of accuracy may have greater predictive power than models with higher accuracy. It may be better to avoid the accuracy metric in favor of other metrics such as precision and recall.
Accuracy is often the starting point for analyzing the quality of a predictive model, as well as an obvious criterion for prediction. Accuracy measures the ratio of correct predictions to the total number of cases evaluated. It may seem obvious that the ratio of correct predictions to cases should be a key metric. A predictive model may have high accuracy, but be useless.
