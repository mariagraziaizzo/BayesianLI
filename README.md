# BayesianLI
The linear bayesian inference py code makes linear bayesian regression on a set of input data. It: 1) semi-analytically computes the Log-Evidence function, 2) chooses the optimal model corresponding to the maximum Log-Evidence; 3) calculates the inferred data and the related statistical error in a given interval x_infer, which can be different from the interval definition of the input data, from the predictive distribution; 3) computes the Log-Evidence function and the inferred value of data at x=0 with the related error as a function of the number of input data progressively taken into account.
Most of the code content is inspired by C. M. Bishop, 'Pattern Recognition and Machine Learning' Springer Nature 2011 (Chap. 3).
Useful hints can be found also in Barber, 'Bayesian Reasoning and Machine Learning' Cambridge University Press 2012.

This project is licensed under the terms of the GNU General Public License v3.0.
