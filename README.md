# Project 1 

Put your README here. Answer the following questions.

* What does the model you have implemented do and when should it be used?
  
Ans :-

The model predicts housing prices by analyzing a dataset with various property attributes such as house size, number of rooms, location details, and other relevant factors. It utilizes Linear Regression with ElasticNet regularization, which balances the L1 (Lasso) and L2 (Ridge) penalties on the model’s coefficients. This helps to prevent overfitting, particularly in datasets with many features or in cases where features may be correlated or redundant.

When to use this model :-

- When the dataset includes many predictors, especially when some of them may be highly correlated or redundant.
- When both feature selection (through L1 regularization) and reducing coefficient size (through L2 regularization) are important to improve generalization.
- When a balanced approach between sparsity and regularization is required to create a more flexible and stable model.


* How did you test your model to determine if it is working reasonably correctly?

Ans :-

I tested the model using a combination of techniques and performance metrics :-

Train-test split :- The dataset was divided into training and testing sets, allowing me to evaluate how well the model generalizes to unseen data.

Cross-validation :-  This method was applied to assess the model’s performance across multiple data splits, reducing the risk of overfitting and providing a more reliable performance estimate.

Performance metrics :- The model’s accuracy was evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²), which measure how well the predicted values align with the actual house prices.

Visual inspection :- I generated plots of predicted values versus actual prices to visually assess the model's accuracy. A strong alignment between these values indicates that the model performs well in predicting house prices.


* What parameters have you exposed to users of your implementation in order to tune performance? (Also perhaps provide some basic usage examples.)

Ans :- 


* Are there specific inputs that your implementation has trouble with? Given more time, could you work around these or is it fundamental?
