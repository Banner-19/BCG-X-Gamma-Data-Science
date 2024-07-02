# What is classification?
* When you are trying to predict an outcome, the result that you’re trying to predict can either be:

  * A continuous number, e.g. an employees salary
  * Or a discrete value, e.g. a job title
* In our example, we are trying to predict whether or not a client will churn, so it will only ever been 1 of 2 values (True/False, 1/0, etc…).
* If the outcome that you’re trying to predict has a fixed number of discrete values, this is a classification problem, as you are trying to “classify” the observations in the data. If the outcome is a continuous number, this is a regression problem. We will not cover regression problems in this task.
# And how does a Random Forest work?
A random forest is a supervised learning algorithm which means that you must provide the algorithm with a set of features, as well as the outcome that you’re trying to predict, in our case churn.

The way it makes predictions is by building a set of decision trees on different samples of the data and by taking a majority vote to decide what prediction to make.

To visualize this, the image below shows 9 decision trees and they are all trying to predict an outcome which is either a 1 or a 0 (similar to our case, where if someone has churned you see a 1, and if they haven’t you see a 0).

The random forest would look at all the predictions generated from the 9 trees. You can see that 6 trees have predicted 1 and 3 have predicted 0. Therefore, the random forest would take the majority vote and present it’s prediction as equal to 1.
![random forest](https://static.javatpoint.com/tutorial/machine-learning/images/random-forest-algorithm2.png)
# Outline for making your predictions
It is your task to:

* Train a random forest classifier to predict churn
* Evaluate the predictions using evaluation metrics to demonstrate how accurately the model has performed

The outputs of your work will be shared with the AD and Estelle has given you a few points to include within the notebook:
* Why did you choose the evaluation metrics that you used? Please elaborate on your choices.
* Do you think that the model performance is satisfactory? Give justification for your answer.
* Make sure that your work is presented clearly with comments and explanations
