## CNN-Based Image Classification on CIFAR-10 Dataset
## Objective
To build and train a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into one of 10 categories and evaluate its performance.
## Project Overview
The CIFAR-10 dataset consists of 60,000 32x32 RGB images, evenly divided into 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. A CNN model was built, trained, and evaluated to recognize patterns and classify these images.The architecture included convolutional layers for feature extraction, max-pooling layers to downsample features, flatten layers to prepare for dense layers, and dense layers for classification. The model was trained using categorical cross-entropy loss and optimized with the Adam optimizer.After training, the CNN achieved a test accuracy of 65%, indicating it could correctly classify 65% of unseen images in the CIFAR-10 dataset.
## Conclusion
The CNN successfully learned to classify CIFAR-10 images with 65% test accuracy. This demonstrates the model's ability to recognize image patterns and generalize across unseen test data. While the results are promising, improvements like data augmentation, hyperparameter tuning, and transfer learning could enhance performance further. This project provided hands-on experience with CNNs and image classification fundamentals.
