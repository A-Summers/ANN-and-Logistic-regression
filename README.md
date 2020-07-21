# ANN-and-Logistic-regression
In the simulated data there are three explanatory variables. I then proceed to use this data to build a logistic regression model, which with a threshold of approx 0.23 gives a true positive rate of 83% and false positive rate of 20%. The feed forward neural network has 1 hidden layer with 1 hidden node and the Leaky ReLU function is applied here, which is defined as f(x) = x for x>=0 and f(x) = 0.01*x otherwise. In the output layer the logistic activation function is used. In the testing stage we can see that the same true and false positive rate is achieved with a smaller threshold of 0.1679. This is likely due to the fact that there is only one node in the hidden layer, so this neuron should be activated strongly since it is the only node in the hidden layer contributing to the output. Hence, because of the leaky ReLU function being using, the input into the hidden layer will likely be the same as the output of the hidden layer in most if not all the cases. Since we are then applying the logistic function at the end, it makes intuitive sense that we would be getting similar predictions at the end.
