Image Classification using Convolutional Neural Networks (CNNs)
This repository contains the implementation of an image classification model using Convolutional Neural Networks (CNNs) in TensorFlow and Keras.

Key Features:
Data Preprocessing: Utilized Keras' ImageDataGenerator for data augmentation (rescaling, shearing, zooming, and horizontal flipping) to enhance the training dataset's diversity.
CNN Architecture: Built a multi-layer CNN model with convolutional, pooling, and fully connected layers. The model is compiled using the Adam optimizer and binary cross-entropy loss function.
Model Training and Evaluation: Trained the model on a prepared dataset and evaluated its performance on the test set across 25 epochs, achieving high accuracy.
Single Image Prediction: Includes functionality to predict the class of a single image (e.g., distinguishing between cats and dogs).
