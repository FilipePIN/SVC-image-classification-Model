#### Custom SVC Image Classification Model

Trains a SVC Computer Vision model using a images from cifar10 or a small set of custom images from 2 different classes.
To change this, change the parameter 'use_cifar10_images' in svc_model_infer.ipynb.
To test the inference, use the 'svc_model_infer.ipynb' notebook and set the parameter there as well. The parameters are independent, it is possible to train with custom images and use cifar10 images to train.