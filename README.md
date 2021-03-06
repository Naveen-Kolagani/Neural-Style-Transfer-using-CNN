# Neural-Style-Transfer-using CNN
### This repo contains the [jupyter notebook](https://github.com/Naveen-Kolagani/Neural-Style-Transfer-using-CNN/blob/master/Art%20Generation%20with%20Neural%20Style%20Transfer.ipynb) describing the implementation of Neural Style Transfer using Convolution Neural Networks

Neural Style Transfer is transfering a picture's style to another. 
* Its implementation is used in the android app PRISMA

#### It is done using a pre-trained VGG19 model which is equivalent to transfer learning. All the pretrained models are trained on GPUs
* This is the [link](http://www.vlfeat.org/matconvnet/pretrained/) to all the pretrained models available.
* Download the model and save it in the folder where jupyter notebook file is present.

The *input* and *outputs* are in their respective folders. The model ran on few iterations so the output might not be impressive.
The [nst_utils.py](https://github.com/Naveen-Kolagani/Neural-Style-Transfer-using-CNN/blob/master/nst_utils.py) contains necessary functions to resize, normalize and to generate noise image.

*NOTE:* 
##### Use GPU if its installed on your PC or use cloud services like Google Colaboratory etc to carry out the model for large number iterations say 50000 for best results.
