
## Overview

Face recognition using transfer learning Here , i have applied VGG16 to do prediction. My dataset contain 5 folders in which there are 5 celebrities so based on this we will do prediction.  

There are various types of  transfer learning model for image classification such as
* Xception
* VGG16
* VGG19
* ResNet50
* InceptionV3
* InceptionResnet
* MobileNet
* DenseNet
* NASNet
* MobileNetV2

Here, We are going to use VGG16 to train the model.VGG16 is a pre-trained model.


## Pre trained model

A pre-trained model has been previously trained on a dataset and contains the weights and biases that represent the features of whichever dataset it was trained on. Learned features are often transferable to different data. For example, a model trained on a large dataset of bird images will contain learned features like edges or horizontal lines that you would be transferable to your dataset.

Pre-trained models are beneficial to us for many reasons. By using a pre-trained model you are saving time. Someone else has already spent the time and compute resources to learn a lot of features and your model will get benefit from these pre-trained weights.

## VGG16

VGG16 is a convolution neural net (CNN ) architecture which was used to win ILSVR(Imagenet) competition in 2014. It is considered to be one of the excellent vision model architecture till date. Most unique thing about VGG16 is that instead of having a large number of hyper-parameter they focused on having convolution layers of 3x3 filter with a stride 1 and always used same padding and maxpool layer of 2x2 filter of stride 2. It follows this arrangement of convolution and max pool layers consistently throughout the whole architecture. In the end it has 2 FC(fully connected layers) followed by a softmax for output. The 16 in VGG16 refers to it has 16 layers that have weights. This network is a pretty large network and it has about 138 million (approx) parameters.
![vgg16](https://user-images.githubusercontent.com/47081733/204126257-798cd15c-eb01-423c-83db-e9d1905b6a95.jpg)


Project Link
---
Github: https://github.com/pushkya/FaceRecognition
