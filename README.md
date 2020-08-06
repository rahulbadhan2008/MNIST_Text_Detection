# MNIST-Number-Detection-using OpenCV and Keras

First step towards building an efficient number detection system by using MNIST data . Implemented the CNN ALEX Net algorithm from scratch (no object detection API used) for the specific task in python using keras and tensorflow.

## Data : 

The dataset used is MNIST number data which available in Keras  
<br />
Train images = 60000 <br />
Validation images = 10000

## Preprocessing :

The `preprocessors.py` file handles all the necessary preprocessing and  use to draw contours make squar and resize the image pixel

### Custom data :
Necessary changes need to be done in the `preprocessors.py` file to input the custom data and images, to create the appropriate input and output matrices. 

## Model :

ALEXNET architecture is used as a feture extractor. The main reason for choosing ALEXNET is the high accuracy . Relu is the activaion function working with this nural network.


## Loss Function and Training:

The loss function implemented is the one specified in the ALEXNET. As there is only 10 classes to be predicted, the loss function is used categorical_crossentropy.
<br />

The model is trained for 5 epochs in total with a batch size of 128.  The learning rate was kept at 0.001 for the 5 epochs. 



## testImages :

Test images is used to detect real time hand written data

## Requirements : 

1. Keras 
2. Tensorflow : 1.15.0 
3. OpenCV 
4. Numpy  
5. Matplotlib 

## Open Neural Network Exchange (ONNX) 

ONNX is an open format built to represent machine learning models. ONNX defines a common set of operators - the building blocks of machine learning and deep learning models - and a common file format to enable AI developers to use models with a variety of frameworks, tools, runtimes, and compilers



## TEST
To test the real time data Text_Test.ipynb file is used 















