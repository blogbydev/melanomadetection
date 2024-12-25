This project demonstrates how I built a Convolutional Neural Network (CNN) to detect melanoma by classifying skin lesions into 9 categories. The model preprocesses image data, extracts features through convolutional layers, and predicts lesion types using a fully connected softmax layer.

Model Architecture:

Input Preprocessing:
- I rescaled the images to normalize pixel values to the range [0, 1].

Feature Extraction:
- I used two convolutional layers with ReLU activation, followed by max-pooling and dropout to prevent overfitting.

Classification:
- The extracted features are flattened and passed through a batch-normalized dense layer for better representation.
- The final predictions are made using a softmax activation function across 9 classes.

Key Features:
- Dropout Regularization: I included dropout layers to mitigate overfitting during training.
- Batch Normalization: This helped stabilize training and improve convergence.
- Categorical Classification: The model predicts one of nine skin lesion categories.

This model reflects my effort to develop an effective melanoma detection system using deep learning techniques.
