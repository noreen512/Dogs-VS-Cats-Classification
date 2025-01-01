# Dogs-VS-Cats-Classification
https://colab.research.google.com/drive/1g6djFqdRtOrInz7Kzp958HC1kV8TOIvM?usp=sharing

This project implements a binary image classification model to distinguish between cats and dogs using a convolutional neural network (CNN). Built and trained in Google Colab, the model processes images resized to 150x150 pixels and uses TensorFlow/Keras for development.

Key Features:
Architecture: A sequential CNN model with three convolutional layers, max-pooling layers, and a fully connected dense layer for feature extraction and classification.
Activation Functions: ReLU activation in hidden layers for non-linearity and a sigmoid activation in the output layer for binary classification (cats or dogs).
Binary Crossentropy Loss: Optimized using binary crossentropy, suitable for binary classification tasks.
Real-World Dataset: Uses the Cats vs Dogs dataset for training and testing.
