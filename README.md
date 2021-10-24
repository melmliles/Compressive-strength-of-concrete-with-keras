# Compressive-strength-of-concrete-with-keras

1. Topic:

In this project, we will build a regression model using the Keras library to model the concrete compressive strength.

2. Concrete Data:

The data can be found here: https://cocl.us/concrete_data. To recap, the predictors in the data of concrete strength include:

-Cement
-Blast Furnace Slag
-Fly Ash
-Water
-Superplasticizer
-Coarse Aggregate
-Fine Aggregate

* PART A:

Build a baseline model, where we will use the Keras library to build a neural network with the following:

-One hidden layer of 10 nodes, and a ReLU activation function

-Use the adam optimizer and the mean squared error  as the loss function.

1. Randomly split the data into a training and test sets by holding 30% of the data for testing. 

2. Train the model on the training data using 50 epochs.

3. Evaluate the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength.

4. Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.

5. Report the mean and the standard deviation of the mean squared errors.

* PART B:

To evaluate the impact of a normalized data on the results, we will repeat Part A but we will use a normalized version of the data. Recall that one way to normalize the data is by subtracting the mean from the individual predictors and dividing by the standard deviation.

* PART C:
Increate the number of epochs:
We will repeat Part B but with 100 epochs this time for training --> Evaluate how does the mean of the mean squared errors compare to that from Step B.

* PART D:
Increase the number of hidden layers:

We will repeat part B but use a neural network with the following instead:

-Three hidden layers, each of 10 nodes and ReLU activation function.

--> Evaluate how does the mean of the mean squared errors compare to that from Step B.


