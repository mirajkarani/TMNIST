# TMNIST Classification for Character Recognition 

### Technology Used

1. CNN (Deep Learning)
2. TensorFlow
3. Pandas
4. Matplotlib
5. Python

### Model Parameters

In this notebook, I have used the Keras API to build a simple neural network using a sequential model. The CNN consists of multiple layers:

- In this model, I have used 3 Convolutional layers with 32 and 64 filters and kernel of size 3x3 and L2 regularization with a hyperparameter of 0.0005.
- I have added a dropout of 20% to reduce overfitting on training data by disregarding some of the neurons.
- I have 2 dense layers in the CNN of size 256 and 10 in the final layer (as we have 10 output classes).
- I have used Adam optimizer for compiling the model with cross-entropy as the loss function and accuracy will be used to evaluate the model performance.
- I have used 25% for the validation split and 10 epochs with a batch size of 100.

![Convolutional Neural Network](https://camo.githubusercontent.com/b9a5886d86a1d2fc2634c2a42063ead4610a142616d0fb989402b3bfe5ea7360/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313230302f312a766b5130685844615176353773414c58414a717578412e6a706567)

### Model Accuracy

![Model Accuracy](https://i.imgur.com/bMeOTQh.png)

We have a simple neural network that can predict the characters in the TMNIST dataset with an accuracy of 98%.
