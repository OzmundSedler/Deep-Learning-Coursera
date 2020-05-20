## Week 1 - Practical aspects of Deep Learning

1. Train/test/dev sets. How will you split 10k dataset. 1m dataset?
2. Explain bias/Variance tradeoff.
3. Types of regularization. NN example. Why regularization reduces overfitting?
![reg](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%201/images/Screenshot%202020-05-08%20at%2022.14.42.png)
4. Explain dropout regularization. What is the principle behind it. Why does it works?
5. What is data augmentation and how it is used?
6. What is early stopping and how it is used?
7. Why do you need input normalization in NN?
8. Explain vanishing/exploding gradients problem.
9. How you need to initialize weights in Deep NN? What types of initialization do you know?
10. Gradient checking
![GD1](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%201/images/Screenshot%202020-05-08%20at%2022.26.29.png)
![GD2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%201/images/Screenshot%202020-05-08%20at%2022.27.07.png)


**Questions from quiz**
11. If your Neural Network model seems to have high bias, what will you try?
12. You are working on an automated check-out kiosk for a supermarket, and are building a classifier for apples, bananas and oranges. Suppose your classifier obtains a training set error of 0.5%, and a dev set error of 7%. What will you try to improve your classifier?
13. What is weight decay?
14. What happens when you continue to increase the regularization hyperparameter lambda?
15. With the inverted dropout technique, what will you do at test with your NN?
16. Increasing the parameter keep_prob from (say) 0.5 to 0.6 in dropout will likely cause the following:
- ...... the regularization effect
- Causing the neural network to end up with a ... training set error
17. Give examples of techniques useful for reducing variance (reducing overfitting)?
18. Why do we normalize the inputs x?


## Week 2 - Optimization algorithms

1. What is mini-batch GD? How will you choose MB size?
2. Explain exponentially weighted average.
 What are the principles behind it and when it is appropriate?
3. Bias correction in EWA. Gradient descent with momentum. 
3. RMSprop
4. Adaptive moment estimation optimization algorithm (adam). Algorithm and the math behind it.
5. Explain the problem of learning rate decay. Name some learning rate decay methods.
6. The problem of local optima in NN. What is the saddle point?


**Questions from quiz**

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

## Week 3 - Hyperparameter tuning, Batch Normalization and Programming Frameworks

1. Batch normalization. The formula for batch norm. Why does it work (intuition)?
![BN](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%203/images/Screenshot%202020-05-12%20at%2008.31.13.png)
2. What is the purpose of gamma and beta in Batch Norm? How they can be learned?
3. The process of fitting batch norm to NN network.
![BN3](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%203/images/Screenshot%202020-05-12%20at%2008.32.56.png)
4. How you can use Batch Norm as regularization.
5. Softmax regression. Softmax layer. The math behind it.
![Softmax](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/2%20Improving%20Deep%20Neural%20Networks%20Hyperparameter%20tuning%2C%20Regularization%20and%20Optimization/week%203/images/Screenshot%202020-05-12%20at%2008.33.47.png)

**Questions from quiz**

6. If searching among a large number of hyperparameters, you should try values in a grid rather than random values, so that you can carry out the search more systematically and not rely on chance. True or False?
7. Every hyperparameter, if set poorly, can have a huge negative impact on training, and so all hyperparameters are about equally important to tune well. True or False?
8. In the normalization formula z(i)norm=z(i)−μσ2+ε√, why do we use epsilon?






