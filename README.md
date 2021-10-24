# Compressive-strength-of-concrete-with-keras

1. Topic:

In this project, we will build a regression model using the Keras library to model the concrete compressive strength.

2. Concrete Data:

The data can be found here: https://cocl.us/concrete_data. To recap, the predictors in the data of concrete strength include:

-Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate

* PART A:

Build a baseline model, where we will use the Keras library to build a neural network with the following:

- One hidden layer of 10 nodes, and a ReLU activation function

- Use the adam optimizer and the mean squared error  as the loss function.

1. Randomly split the data into a training and test sets by holding 30% of the data for testing. 

2. Train the model on the training data using 50 epochs.

3. Evaluate the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength.

4. Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.

5. Report the mean and the standard deviation of the mean squared errors.

