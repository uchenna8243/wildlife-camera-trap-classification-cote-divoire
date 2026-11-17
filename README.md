# Wildlife Camera-Trap Classification (Côte d'Ivoire)

Neural network image classifiers built in PyTorch to identify animal species in camera-trap images from a wildlife preserve in Côte d'Ivoire, supporting conservation monitoring.

## Problem
Camera traps produce thousands of images, and conservation teams cannot label them all by hand. An automatic classifier cuts the time from capture to insight and frees researchers to focus on the animals that matter.

## Process
1. **Data exploration:** loaded the camera-trap images and labels, checked the class balance across species, and viewed sample images from each class.
2. **Pre-processing:** resized the images, converted them to tensors and normalised them, then split the data into training and validation sets.
3. **Baseline model:** built and trained a simple fully connected network as a reference point.
4. **Convolutional neural network:** designed a CNN with convolution, pooling and dropout layers to learn visual features such as shape and texture.
5. **Training and evaluation:** trained with a cross-entropy loss and an optimiser, tracked training and validation loss and accuracy each epoch, and examined a confusion matrix to see which species were mixed up.
6. **Prediction:** generated class probabilities for unseen test images.

## Tools
Python · PyTorch · torchvision · pandas · NumPy · Matplotlib · Jupyter

## Skills shown
Image classification · CNN design · Training loops · Model evaluation · Working with imbalanced classes

## Repository status
The project notebooks and scripts are being prepared for upload and will be added here shortly.

## Programme
Completed as part of the **WorldQuant University Applied AI Lab: Deep Learning for Computer Vision** (Jul 2025).

## Author
**Uchenna Francis Onyeka** · MSc FinTech with Business Analytics, University of Westminster
[LinkedIn](https://www.linkedin.com/in/uchenna-onyeka) · [GitHub](https://github.com/uchenna8243)
