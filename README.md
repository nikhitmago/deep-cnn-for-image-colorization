# Deep CNN for Image Colorization

- The data set for this task is [CIFAR-10](http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)
- Using a tensorflow backend
- From 6000 images, we chose 10% of the pixels where each pixel is an RGB vector with three elements.
- We use clusetring to obatin the outputs of the network by converting the colored images to k-colored images
- The input of the network is created by converting the original image to grayscale
- For the CNN, we use 2 convolution layers, 2 MLP layers with 5 * 5 filters and a softmax layer, and one max pooling layer
