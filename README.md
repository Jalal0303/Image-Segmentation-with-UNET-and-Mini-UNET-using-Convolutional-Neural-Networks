# Image-Segmentation-with-UNET-and-Mini-UNET-using-Convolutional-Neural-Networks
The Project focuses on the task of Image Segmentation using UNET and Mini-UNET using CNN.

In this project we will work with the Oxford-IIIT pet dataset.1 The Oxford-IIIT pet
dataset is a 37 category pet image dataset with roughly 200 images for each class. The
images have large variations in scale, pose and lighting. All images have an associated
ground truth annotation of breed. Here we do not want to classify the 37 cat and dog
categories, we want to train and predict the segmentation. For that we need training data
that are annotated with segmentations masks, which is the case for the cats and dogs
of this dataset. The learning task is to predict pixelwise if a pixel belongs to cat/dog,
background or margin.

We will first use groups a linear stack of layers to create UNET model and in the second task will implement our own Mini-UNET.
