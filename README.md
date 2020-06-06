# CNN-Image-classifier-for-horses-and-humans
This is a project done by using Tensorflow 2.0 to classify images into two classes being Horses or Humans.
The dataset used for training is a CGI generated dataset of Horses and Humans with a training data of 1027 images of 2 classes and a validation dataset of 256 images of 2 classes.
A sequential model is used with 3 convolutional layer, a flatten layer, a dropout layer to help balance overfitting, 2 dense layers and an output layer with sigmoidal activation function.
In order to use a small dataset more efficiently ImageDataGenerator is used.

