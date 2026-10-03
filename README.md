# machine_learning_for_derivative_product

In this repository, we are going to see how we can evaluate path dependent option like Bermudan Option using Machine Learning. It will be separate in 3 parts : 

## 1 - CRR model

This is simple binomial model that allows us to understand the principle of the Longstaff-Schwarz and the backwarding reasoning.

## 2 - Algorithm of Longstaff-Schwartz (LS)

In this algorithm we present the algorithm of Longstaff-Scwartz. In this algorithm, we need to approwimate conditionnal expectation ($\mathbb{E}[X|Y]$). Here we present the linear regression to approximate it. In this notebook, I present the first two methods I used without so much mathematicals properties to fit the linear regression. 

## 3 - Comparison LS using Linear Regression (OLS) and using Neural Network (NN)

Here, again we apply the Longstaff-Schwartz to price Bermudan option. Here we present two ways of doing it. The first one is still the Linear Regression but we present the formulas to correctly apply it. Then we try to improve the result using a Neural Network (Multi Layer Perceptron)
