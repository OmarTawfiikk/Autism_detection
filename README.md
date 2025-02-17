# Autism_detection

## Project Overview

This project utilizes a VGG16-based deep learning model to detect autism spectrum disorder (ASD) from facial images. The model achieves an 81% accuracy on the test set and incorporates essential preprocessing techniques such as normalization and data augmentation. Built with TensorFlow/Keras, this implementation demonstrates the effectiveness of transfer learning for medical image classification.

## key Features

-VGG16 Transfer Learning: A pretrained VGG16 model fine-tuned for ASD detection.

-Data Preprocessing:

-Normalization (rescale=1./255)

-Data augmentation (rotation, width/height shift, shear, zoom, flip)

-Early Stopping: Helps prevent overfitting during training.

-High Accuracy: Achieves 81% accuracy on unseen test data


## Model Architecture  

The model consists of the following layers:

-VGG16 Base Model (Pretrained on ImageNet, used for feature extraction)

-Flatten Layer (Converts feature maps into a 1D vector)

-Fully Connected Layer (128 Neurons)

-Dropout Layer (Prevents overfitting)

-Output Layer (Binary classification with sigmoid activation)

-Total trainable parameters: 1,048,833

## Training Results

-Test Accuracy: 81%

-Training Visualization: Accuracy and loss curves can be plotted to monitor model performance.

## Conclusion

This project demonstrates the power of transfer learning in medical image classification, achieving promising results for ASD detection. Further improvements can be made by experimenting with different architectures, optimizing hyperparameters, and using a larger dataset
