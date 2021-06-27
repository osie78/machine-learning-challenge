# machine-learning-challenge

4 ML models were developed to compare accuracy among all of them:
For all the models, the original dataset was modified to eliminate variables that would have little to none effect in the prediction models. Also a Min/Max Scaler was used as indicated. Tests were conducted with the Standard Scaler function and no difference was obtained. 

* Logistic Regression Model: With this model a F1-score of 0.54 was obtained. A grid searc variying "C" and the max number of iterations was run, but the used parameters did not improved the default values of the "LogisticRegression()" function. 
* Logistic Regression using SVC: The testing data was also around 0.54 of accuracy for the fi-score. 
* Random Forest Model: More dimensions were droped in this model after running the "importance" function. This allowed the test score to increase to 0.59. 
* Deep Learning Model: 192 * 3 layers and 32 input dimensions were used to obtain an accuracy of 0.68. 

It is expected that reducing more columns with less importance, all the adjustments and predictions will improve significantly. 
