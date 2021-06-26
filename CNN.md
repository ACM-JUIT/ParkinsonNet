# CNN (Convolutional Neural Network)

##  Definition 
A **Convolutional Neural Network (ConvNet/CNN)** is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other.
The pre-processing required in ConvNet is very low compared to other classification algorithms. 

![image](https://user-images.githubusercontent.com/75668411/122641279-efaab480-d121-11eb-8afa-6ab5c3ef5f55.png)

### Convolution 
The objective of the Convolution Operation is to extract the high-level features such as edges, from the input image. ConvNets need not be limited to only one Convolutional Layer. Conventionally, the first ConvLayer is responsible for capturing the Low-Level features such as edges, colour, gradient orientation, etc. With added layers, the architecture adapts to the High-Level features as well, giving us a network, which has the wholesome understanding of images in the dataset, similar to how we would.

### Pooling
Similar to the Convolutional Layer, the Pooling layer is responsible for reducing the spatial size of the Convolved Feature. This is to decrease the computational power required to process the data through dimensionality reduction. Furthermore, it is useful for extracting dominant features which are rotational and positional invariant, thus maintaining the process of effectively training of the model.
There are two types of pooling (a) Max Pooling (b) Average Pooling
(a)	 Max Pooling: It takes a maximum of the spatial size and store it in a less spatial size by reducing its dimensions. 
(b)	 Average Pooling: It takes the average of the spatial size and store it.
Max Pooling works a lot better than average pooling.

The Convolutional Layer and the Pooling Layer, together form the i-th layer of a Convolutional Neural Network. Depending on the complexities in the images, the number of such layers may be increased for capturing low-levels details even further, but at the cost of more computational power.

### ReLU
ReLU converts all negative values to zeros to bring linearity in the feature map.
This decreases the computation of the features of the image a lot.

**You can have as many as ConvNets as you like the more you will have the more the features from the image are extracted.**

![image](https://user-images.githubusercontent.com/75668411/122641344-4adca700-d122-11eb-909a-8fdb82f84bd7.png)

### Softmax
The softmax, or “soft max,” mathematical function can be thought to be a probabilistic or “softer” version of the argmax function.
This function is used as the activation function in the output layer of neural network models that predict a multinomial probability distribution.
That is, softmax is used as the activation function for multi-class classification problems where class membership is required on more than two class labels.

### Final Computation 
Convolutional + ReLU + Pooling gives only the feature part but classification of image at final stage using neurons are done by classification algorithms.
There are many classification algorithms but here in Parkinson Disease we will use the most popular one which is SoftMax activation function.
SoftMax is a mathematical function that converts a vector of numbers into a vector of probabilities, where the probabilities of each value are proportional to the relative scale of each value in the vector.
The most common use of the SoftMax function in applied machine learning is in its use as an activation function in a neural network model. Specifically, the network is configured to output N values, one for each class in the classification task, and the SoftMax function is used to normalize the outputs, converting them from weighted sum values into probabilities that sum to one. Each value in the output of the SoftMax function is interpreted as the probability of membership for each class.
