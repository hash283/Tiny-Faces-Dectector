# Tiny-Faces-Dectector
A face detection model capable of detecting faces of various scales and sizes. This is trained using a Multi-Branch FCNN and modified Super Resolution GAN. Implementation of the paper [Finding Tiny Faces](https://arxiv.org/abs/1612.04402)

### Introduction
The paper - released at CVPR 2017 - deals with finding small objects (particularly faces in our case) in an image, 
based on scale-specific detectors by using features defined over single (deep) feature hierarchy : 
Scale Invariance, Image resolution, Contextual reasoning. The algorithm is based on foveal descriptors, i.e blurring the peripheral image to encode and give just enough information about the context, mimicking the human vision. The code present in this repo is an implementation of the model using TensorFlow and OpenCV2.
