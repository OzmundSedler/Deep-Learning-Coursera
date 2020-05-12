## Questions

## **Optimization algorithms**

1. What is mini-batch GD? How will you choose MB size?
2. Explain exponentially weighted average.
 What are the principles behind it and when it is appropriate?
3. Bias correction in EWA. Gradient descent with momentum. 
3. RMSprop
4. Adaptive moment estimation optimization algorithm (adam). Algorithm and the math behind it.
5. Explain the problem of learning rate decay. Name some learning rate decay methods.
6. The problem of local optima in NN. What is the saddle point?


## Questions from quiz

7. Suppose your learning algorithm’s cost JJ, plotted as a function of the number of iterations, looks like this. Which GD are you using?
![Loss func](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%202/images/Screenshot%202020-05-12%20at%2008.14.18.png)
8. You use an exponentially weighted average on the London temperature dataset.
 You use the following to track the temperature: vt=βvt−1+(1−β)θt.
  The red line below was computed using β=0.9.
   How oscillation will change if you will decrease β? 
   What will cause the red line shift slightly to the right?
![London](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%202/images/Screenshot%202020-05-12%20at%2008.13.24.png)
9. These plots were generated with gradient descent; with gradient descent with momentum (\betaβ = 0.5) and gradient descent with momentum (\betaβ = 0.9). Which curve corresponds to which algorithm?
![GD](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%202/images/Screenshot%202020-05-12%20at%2008.13.28.png)
10. Suppose batch gradient descent in a deep network is taking excessively long to find a value of the parameters that achieves a small value for the cost function J.
 Which techniques could help find parameter values that attain a small value for J? 
