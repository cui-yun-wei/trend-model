# trend-model
For the paper of Zheng, Cui, and Wu. 

Here we provide the R code to estimate the smooth function and the ARMA parameters by least squares method in one step. 

Remarks:

1. To avoid multicollinearity, one column of the basis function matrix is deleted. 

2. To ensure the random error process has a mean equal to zero, the y variable is centered with mean equal to zero and the basis function matrix is also column centered, i.e., the column mean is subtracted from each column. 

3. We set the initial values of the optimization process to be random numbers uniformly distributed on the interval (0, 1) and the coefficients all equal to one for the basis functions. The initial values could also be set equal to the estimates from the sequential method. 
For AR(2) or MA(2) process, the initial values will not be accepted unless all roots are outside the unit circle. 
"# trend-model" 
