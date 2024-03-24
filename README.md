# Transfer-Learning-and-Data-Augmentation-for-Image-Classification

This repository contains code for performing image classification using transfer learning and data augmentation techniques. The goal is to classify images into two classes using a limited amount of data.

## Introduction
In this exercise, we aim to classify images into two classes using transfer learning and a small dataset. We employ data augmentation techniques to increase the size of the training, evaluation, and test datasets. The final datasets consist of:
- **Training Data**: 2000 images (1000 images per class)
- **Evaluation Data**: 1000 images (500 images per class)
- **Test Data**: 1000 images (500 images per class)

## Approach
### Data Augmentation
We use various data augmentation methods to increase the size of our datasets while preserving the underlying characteristics of the images.

### Transfer Learning
We leverage pre-trained models such as VGG, MobileNet, etc., for transfer learning. We fine-tune these models on our augmented datasets. Different numbers of layers are frozen during fine-tuning to observe their impact on classification performance. For instance, we experiment with freezing the last 3, 5, and 7 layers of the networks.

## Results
We compare the performance of different fine-tuning strategies by evaluating them on the test dataset. The results demonstrate the effectiveness of transfer learning and the impact of freezing different numbers of layers.

## Conclusion
Transfer learning combined with data augmentation proves to be a powerful technique for image classification, especially when dealing with limited data. By fine-tuning pre-trained models and employing data augmentation, we can achieve significant improvements in classification accuracy.

