# linear-regression-from-scratch

The following repository is a short outline of how a basic linear regression machine learning model works, by implementing the mathematics from scratch using Numpy. 

The "lr.ipynb" notebook provides a walkthrough of what linear regression is, how we find the optimal model parameters via gradient descent. The notebook ends with a comparison with the standard scikit-learn implementation of linear regression to demonstrate that both approaches converge to almost identical solutions.

A "lm_model.npy" file is produced by the notebook which stores the weights from the implemented model, which in a more realistic scenario may be used for real-world predictions on unseen data.

Further additions could be made to improve this model, such as using L2 regularisation, which are not implemented here.