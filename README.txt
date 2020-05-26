
This Red Wine Quality dataset from Kaggle. Goal is to predict
the quality of wine based on other given data.

This datasets is related to red variants of the Portuguese "Vinho Verde" wine. 
The datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more 
normal wines than excellent or poor ones). We modeled the problem here as a regression problem.

Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

We used Artificial Neural Network (ANN) for modeling this regression problem.

Results:

Mean-Squared-Error(MSE) = 0.5802087225600538

Mean-Absolute-Error(MAE) = 0.5969653897530834

RMSE = 0.7617143313342961


Epoch 200/200
1279/1279 [==============================] - 0s 274us/step - loss: 0.5726 - val_loss: 0.5802

