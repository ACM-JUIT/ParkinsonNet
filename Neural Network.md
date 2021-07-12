# Machine Learning 
Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on **the development of computer programs** that can access data and use it to learn for themselves.
whereas  **Neural network** is a *subset of machine learning* inspired by the workings of the human brain.

![image](https://user-images.githubusercontent.com/85950108/125219836-333cac80-e2e3-11eb-8526-6d8f7756a94e.png)


## Neural Network(Defination)

Neural networks reflect the behavior of the **human brain**, allowing computer programs to recognize patterns and solve common problems in the fields of AI, machine learning, and deep learning.

## What is Neural Network

Networks , also known as **Artificial neural networks (ANNs)** , are a subset of machine learning and are at the heart of Deep Learning Algorithms. Their name and structure are inspired by the human brain.

![image](https://user-images.githubusercontent.com/85950108/125197342-d60d1080-e27a-11eb-9153-009e6d1a0763.png)

whereas neural networks rely on training data to learn and improve their accuracy over time. However, once these learning algorithms are fine-tuned for accuracy, they are powerful tools in computer science and artificial intelligence, allowing us to classify and cluster data at a high velocity.
Now let us see types of **Neural Networks** .

## Types Of Neural Networks

As we know that Neural Network is a very vast field with deals with data processing so there are many types of Neural Network but mainly we have three types of Neural Network and those are:

### 1. ANN (Artificial Neural Networks) / Feed Forward Neural Network :
Artificial neural networks (ANNs) are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer. Each node, or artificial neuron, connects to another and has an specific value associated with it . If the output of any individual node is same to that of the specified value than the  node gets activated, sending data to the next layer of the network. Otherwise, no data is passed along to the next layer of the network.
and that is why ANN is also known as a **Feed-Forward Neural network** because inputs are processed only in the forward direction.

![image](https://user-images.githubusercontent.com/85950108/125221696-44d38380-e2e6-11eb-8936-a961e9a831e6.png)

The main advantage of ANN is that it is capable of Learning any **nonlinear function** . Hence, these networks are popularly known as Universal Function Approximators *(In the mathematical theory of **Artificial neural networks**, the universal approximation theorem states that a feed-forward network with a single hidden layer containing a finite number of neurons can approximate continuous functions on compact subsets of Rn, under mild assumptions on the activation function)*.
whereas the **Disadvantages or challenges** with *Artificial Neural Network* is:

1. While solving an image classification problem using ANN, the first step is to convert a **2-dimensional image into a 1-dimensional vector** prior to training the model. This has two drawbacks:

   a. The number of trainable parameters increases drastically with an increase in the size of the image
   
   b. ANN loses the **spatial features**( Spatial features refer to the arrangement of the pixels in an image.) of an image.

2. ANN cannot capture sequential information in the input data which is required for dealing with sequence data.

Now to overcome these **drawback of ANN** we have other two major type of Neural Network those are : *Recurrent Neural Networks (RNN) and Convolution Neural Networks (CNN).*

### 2. RNN (Recurrent Neural Network) :
The major difference between RNN and ANN is that a **looping constraint on the hidden layer** of ANN turns it into RNN.

![image](https://user-images.githubusercontent.com/85950108/125228068-b2d17800-e2f1-11eb-8005-96e57866f3fc.png)

Now from the figure above we can clearly see the difference in ANN and RNN i.e is RNN has a recurrent connection on the hidden state. This **looping constraint** ensures that sequential information is captured in the input data.

The **major Advantages** of RNN are as follow:

 1.RNN captures the sequential information present in the input data i.e. dependency between the words in the text while making predictions.
 
 2.RNNs share the parameters across different time steps. This is popularly known as Parameter Sharing. This results in fewer parameters to train and decreases the computational cost.
 
Whereas **Disadvantages or challenges** with RNN is :  
 
 Deep RNNs (*RNNs with a large number of time steps*) also suffer from the vanishing and exploding gradient problem **(In the first case, the term goes to zero exponentially fast, which makes it difficult to learn some *long period dependencies.* This problem is called the vanishing gradient. In the second case, the term goes to *infinity exponentially fast*, and their value becomes a NaN due to the unstable process. This problem is called the exploding gradient.)** which is a common problem in all the different types of neural networks.
 
 ![image](https://user-images.githubusercontent.com/85950108/125229615-ca5e3000-e2f4-11eb-9412-1b5a78780bc6.png)

Now let us see the most important type of Neural Network;

### 3. CNN (Convulation Neural Network) :
The major difference between CNN and ANN is that The "layers" in **ANN** are rows of data points hosted through neurons that all use the same neural network.
Comparatively. there is no neuron or weights in CNN. CNN instead casts multiple layers on images and uses filtration to analyze image inputs.

![image](https://user-images.githubusercontent.com/85950108/125230701-f975a100-e2f6-11eb-85a1-8c949f7ff1c9.png)

 CNN models are being used across different applications and domains, and they’re especially prevalent in image and video processing projects. **And our model is also based on CNN**
 
 whereas the The building blocks of CNNs are filters known as  **kernels.** Kernels are used to extract the relevant features from the input using the convolution operation **(A convolution is the simple application of a filter to an input that results in an activation.)** .
 and CNN even perform impressively on sequential inputs as well.
 
 The **major Advantages** of CNN are as follow:
  
  1. CNN learns the filters automatically without mentioning it explicitly. These filters help in extracting the right and relevant features from the input data
 
  2. CNN captures the **spatial features** from an image.
  
  3. CNN also follows the concept of parameter sharing. A single filter is applied across different parts of an input to produce a **feature map** *(The feature map is the output of one filter applied to the previous layer.)*. 
 
 Whereas **Disadvantages or challenges** with CNN is :

We need a large training data whereas it does not  encode the position and orientation of object.
 
