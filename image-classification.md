# Image classification

Image classification refers to labelling of images into one of a number of predefines classes. Image classifying can be used to detect Parkinson in its early stages. This classification is generally done manually. Automating this task can be a great aid for both patients and medical professionals.
### Steps for Image Classification 
*	Image pre-processing
*	Feature extraction
*	Training Model
*	Classification

## Image Pre-processing
The aim of pre-processing is an improvement of the image data that suppresses unwilling distortions or enhances some image features important for further processing.
### Data Augmentation
Data Augmentation techniques are used to give better generalisation of the problem to deep learning models by increasing the number of samples in training dataset.
The type of image data augmentation being used here involves creating transformed versions of images in the training dataset that belongs to the same class as the original image. Transforms include a range of operations from the field of image manipulation, such as shifts, flips, zooms, matching the context of training dataset and understanding of the problem domain. 

![image](https://user-images.githubusercontent.com/72248438/124350662-89d72600-dc13-11eb-81d3-9e6bc948c4ad.png)

## Algorithms for image classification

Image classification can be done using various methods and algorithms. Different algorithms are efficient for different kind of problems and datasets.
## Machine learning algorithms
###	Support Vector Machines
It is a supervised machine learning algorithm which when used for classification purposes separates the classes using a linear boundary.
The real power of this algorithm depends on the kernel function being used.
The most commonly used kernels are:  
*	Linear Kernel
*	Gaussian Kernel
*	Polynomial Kernel


###	Decision Trees
It is also a supervised machine learning algorithm, which at its core is the tree data structure that uses a couple of if/else statements on the features selected.
Decision trees are based on a hierarchical rule-based method and permits the acceptance and rejection of class labels at each intermediary stage/level.

![image](https://user-images.githubusercontent.com/72248438/124350679-a5dac780-dc13-11eb-9dce-4ce6f91a78b1.png)

###	KNN (K nearest neighbours)
This algorithm simply relies on the distance between feature vectors and classifies unknown data points by finding the most common class among the k-closest examples.

## Deep learning algorithms
### ANN (Artificial Neural Networks)
Artificial Neural Networks are statistical learning algorithms that are used for a variety of tasks, from relatively simple classification tasks to computer vision and speech recognition.

ANNs are implemented as a system of interconnected processing elements, called nodes, which are functionally analogous to biological neurons. The connections between different nodes have numerical values, called weights, and by altering these values in a systematic way, the network is eventually able to approximate the desired function.

###	CNN (Convolutional Neural Networks)
CNN is one of the most popular neural network algorithm used in image classification. As the name suggests CNN uses convolution in place of general matrix multiplication in at least one of its layers.

A CNN layer consists of 3 stages: 
*	Convolution stage
*	Detector stage
*	Pooling stage

![image](https://user-images.githubusercontent.com/72248438/124350689-b2f7b680-dc13-11eb-9929-3e6d00bc03ce.png)

## Back Propagation
Back propagation is a supervised learning algorithm that is used to train neural networks.
While training the model we initialise some random weights and because of this randomisation the error value is high. In order to minimise this error function, we need to iterate over the model many times and adjust the weights effectively. The method of propagating the network backwards and adjusting the weights in order to minimise error function is called back propagation.

![image](https://user-images.githubusercontent.com/72248438/124350729-01a55080-dc14-11eb-9ab3-2512b4154a2d.png)
