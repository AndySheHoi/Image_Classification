# Simple_digit_classifier + Demo
It is a combination of the transfer learning application which based on Google Colab.
To test it, please remember to change the save/load path in both files.

# Digits_Classification
Image Classification with MNIST Handwritten Digit Classification Dataset

![alt text](https://adeshpande3.github.io/assets/Cover.png)
## Reference： https://www.tensorflow.org/tutorials/quickstart/advanced

# **Zero Padding**<br> 
With Zero Padding, the convolution layer is the same size as the original
image (or the previous layer).<br>
Kernel size (Receptive field): [4, 4]<br>
![alt text](https://xrds.acm.org/blog/wp-content/uploads/2016/06/Figure_3.png)

# **Max Pooling**<br> 
MaxPooling is the process of downsampling the image. For all values in each sliding window, the maximum value is output.
![alt text](https://cdn-images-1.medium.com/freeze/max/1000/1*GksqN5XY8HPpIddm5wzm7A.jpeg?q=20)

# **Activation functions**<br>
The activation function is to increase the nonlinearity of the neural network model. Each layer without an activation function is equivalent to matrix multiplication

# **Why ReLU?**
1.   When using functions such as sigmoid, the calculation amount is large, and using the Relu activation function, the calculation amount is saved a lot.
2.   For deep networks, when the sigmoid function is back-propagated, it is easy for the gradient to disappear (when the sigmoid is close to the saturation region, the transformation is too slow, the derivative tends to 0, this situation will cause information loss), and the deep layer cannot be completed Network training.
3.   Relu will make the output of some neurons to 0, which causes the sparsity of the network, and reduces the interdependence of parameters, alleviating the occurrence of overfitting problems.

![alt text](https://miro.medium.com/max/1192/1*4ZEDRpFuCIpUjNgjDdT2Lg.png)
