# Introduction to Overfitting and Resolution using L1 and L2 Regularization 

## What is overfitting?

A statistical model is said to be overfitted when we feed it a lot more data than it is needed. Consequently, it starts catching noisy data and inaccurate values in the data. As a result, the efficiency and accuracy of the model decreases.
Overfitting refers to a model that models the training data too well.

Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. This means that the noise or random fluctuations in the training data is picked up and learned as concepts by the model. The problem is that these concepts do not apply to new data and negatively impact the models ability to generalize.

Overfitting is more likely with nonparametric and nonlinear models that have more flexibility when learning a target function. As such, many nonparametric machine learning algorithms also include parameters or techniques to limit and constrain how much detail the model learns.

![picture alt](https://github.com/AntarjotSingh/machine-learning/blob/master/Overfitting_and_Regularization/Overfitting_example.png)

## Signal v/s Noise

In predictive modelling, signal refers to the true underlying pattern that helps the model to learn the data.

Noise is irrelevant and random data in the data set.


## How to detect Overfitting?

The main challenge with overfitting is to estimate the accuracy of the performance of our model with new data.
To address it, we can follow given below approaches.

1. We split our intial dataset into training and test data and using this technique, we should be able to approximately test the performance of our model.
Example, we find out that we have accuracy of around 90% on our training set and around 40% accuracy with our test set. This clearly tell us that our model is not efficient as it has a big difference in accuracy levels between training and test set.

2. Design a simplistic model that serves as a benchmark 
