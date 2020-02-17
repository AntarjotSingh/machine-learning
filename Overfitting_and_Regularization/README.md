# Introduction to Overfitting and Resolution using L1 and L2 Regularization 

## What is overfitting?

A statistical model is said to be overfitted when we feed it a lot more data than it is needed. Consequently, it starts catching noisy data and inaccurate values in the data. As a result, the efficiency and accuracy of the model decreases.
Overfitting refers to a model that models the training data too well.

Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. This means that the noise or random fluctuations in the training data is picked up and learned as concepts by the model. The problem is that these concepts do not apply to new data and negatively impact the models ability to generalize.

Overfitting is more likely with nonparametric and nonlinear models that have more flexibility when learning a target function. As such, many nonparametric machine learning algorithms also include parameters or techniques to limit and constrain how much detail the model learns.

For example, decision trees are a nonparametric machine learning algorithm that is very flexible and is subject to overfitting training data. This problem can be addressed by pruning a tree after it has learned in order to remove some of the detail it has picked up.

![picture alt](https://github.com/AntarjotSingh/machine-learning/blob/master/Overfitting_and_Regularization/Overfitting.png)

## Signal v/s Noise

In predictive modelling, signal refers to the true underlying pattern that helps the model to learn the data.

Noise is irrelevant and random data in the data set.


## How to detect Overfitting?
