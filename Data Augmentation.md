# Data Augmentation in Keras

Image data augmentation is a technique that can be used to artificially expand the size of a training dataset by creating modified versions of images in the dataset

This is a technique to artificially create new training data from existing training data. This is done by creating transformed versions of images in the training dataset that belong to the same class as the original image.

Transforms include a range of operations from the field of image manipulation, such as shifts, flips, zooms, and much more.

 ![image](https://user-images.githubusercontent.com/73527677/125440593-c6937bd6-38d7-48f7-b6b5-cec433c35293.png)

Modern deep learning algorithms, such as the convolutional neural network, or CNN, can learn features that are invariant to their location in the image. Nevertheless, augmentation can further aid in this transform invariant approach to learning and can aid the model in learning features that are also invariant to transforms such as left-to-right to top-to-bottom ordering, light levels in photographs, and more.

Image data augmentation is typically only applied to the training dataset, and not to the validation or test dataset.


## Image Augmentation with ImageDataGenerator

The Keras deep learning library provides the ability to use data augmentation automatically when training a model.

This is achieved by using the ImageDataGenerator Class.

There are five main types of data augmentation techniques for image data:
	Horizontal and Vertical Shift via the width_shift_range and height_shift_range arguments.
	Horizontal and Vertical Flip via the horizontal_flip and vertical_flip arguments.
	Rotations via the rotation_range argument
	Brightness via the brightness_range argument.
	Zoom via the zoom_range argument.

 ![image](https://user-images.githubusercontent.com/73527677/125440652-e173f557-c0fd-489a-89bd-79b182bfc168.png)

First, an instance of the ImageDataGenerator class is constructed.

Once constructed, an iterator can be created for an image dataset. This iterator will return one batch of augmented images for each iteration. 

The iterator is created from an image dataset loaded in memory via the flow() function.

Once the iterator is created, it can be used to train a neural network model by calling the fit_generator() function.
