# Deep Learning with Tensorflow
The files in this repo are my code for the deep learning with tensorflow course released by google on udacity.

# 1_notmnist.ipynb
I learn to curate data using a dataset called notmnist. It is a much messier data set than mnist and contains letters to be classified instead of numbers. After learning to visualize the data, organize it properly, and prepare it for usage, I try some off-the-shelf classifiers from the sklearn library.

# 2_fully_connected.ipynb
I implement a logistic regression model in tensorflow, and then add relu activations to turn it into a neural network. Finally, I try a deep neural network, significantly improving performance on the notmnist dataset

# 3_regularization.ipynb
To prevent overfitting, I implement various forms of regularization. First I try L2 regularization. Then I learn about dropout and try that instead. Although dropout requires increasing the size of the network, it works effectively.

# 4_convolutions.ipynb
A much more effective way to classify the notmnist dataset is a convolutional neural network, since features are images. I try various architectures and regularization methods, mostly experimenting.
