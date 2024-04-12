# Logistic-Regression

The task involved implementing logistic regression on a mechanical failure dataset with 57 features. The dataset was split into a training set of size 3450 and a test set of size 1151. The preprocessing steps were:

(i) Standardization of each column to have mean 0 and unit variance.
(ii) Transformation of features using log transformation xi,j ← log(xi,j + 0.1).
(iii) Binarization of features using xi,j ← I(xi,j > 0).

For each preprocessing method, the following tasks were performed:

(a) Implemented logistic regression using batch gradient descent and plotted the training loss (cross-entropy loss of the training set) vs. the number of epochs.

(b) Derived stochastic gradient descent equations for logistic regression and plotted the training loss vs. the number of iterations. Compared the plots with batch gradient descent.

(c) Implemented stochastic gradient descent with a learning rate that decreases as η ∝ 1/t for the tth iteration. Plotted the training loss vs. the number of iterations to evaluate the strategy compared to a constant learning rate.

(d) Used logistic ridge regression with regularization parameter λ, adjusted based on a validation set (70-30% train-validate split). Derived update equations for logistic ridge regression and generated plots of training and validation loss vs. number of iterations. Reported the best test set error obtained.

The implementation was done without using any software package for logistic regression.
