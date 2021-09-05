# MNIST Example USING KERAS

## INTRODUCTION
MNIST data classification through implementation Convolutional Neural Network using Keras libraries.

## Libraries Used

import numpy as np
import cv2
from matplotlib import pyplot as plt 
from keras.models import Sequential 
from keras.layers import Dense, Dropout, Activation, Flatten  
from keras.layers import Convolution2D, MaxPooling2D
from keras.utils import np_utils

## DATASET
from keras.datasets import mnist (MNIST datset cosists of 28x28 size images of handwritten digits).
