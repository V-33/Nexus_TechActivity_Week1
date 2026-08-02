# Machine Learning Practice
This repository contains my linear regression, logistic regression and KNN models, simply download them and run. The models have a tiny sample data set included. It's not optimized to cope with very large data sets.

1 - Linear Regression:
The aim was to build a linear regression model from scratch without using any external libraries, dot product and gradient descent were both coded manually.
The model takes certain parameters as inputs and computes an output (which is signed decimal value) based on the pre-determined weights and bias (which is obtained from a training data)

- Gradient descent is used to compute weight and bias values by minimizing mean squared error.

2 - Logistic Regression: 
Similar to the linear regression model, this too was created from scratch without usage of external libraries like numpy. 
This model functions similar to Linear Regression except, instead of computing a real number value as an output it chooses from labels. i.e. it classifies the input data into two labels.

- Uses gradient descent to compute weight and bias values by minimizing mean squared error.
- Uses sigmoid activation function.

3 - K Nearest Neighbours:
Again similar to both models mentioned above, the KNN model was also built without help of external libraries. This model contains both linear and logistic regression models.
Unlike the conventional linear and logistic regression models. This does not compute and store weight values. Instead it takes the input values, compares it with "k" neighbours of the closest value to the input value. For logistic regression models, it labels the input with the same label as the most frequently ocurring label amongst its neighbours while for linear regression models, it computes the average output value of the k nearest neighbors and assigns that as the output value.

- Both linear and logistic regression use euclidian distance for classification and prediction of values
