# Plant-Disease-Prediction-Model
In this project, we are designing and implementing a Convolutional Neural Network (CNN) to accurately predict whether a plant is afflicted by a disease based on visual data from leaf images. The CNN model is constructed by leveraging multiple layers such as convolutional, pooling, and fully connected layers to effectively extract and learn complex patterns from the input images. A variety of hyperparameters, including learning rates, batch sizes, and the number of filters, are fine-tuned to optimize model performance. The model is trained, validated, and rigorously tested on a dataset comprising images of healthy and diseased plant leaves.

We utilize TensorFlow and Keras frameworks to develop the classification model, enabling us to build a robust and scalable deep learning architecture. These tools provide flexibility in implementing state-of-the-art techniques, such as data augmentation and early stopping, to improve the model’s generalization and prevent overfitting. The end goal is to deploy this model for real-time disease detection, potentially providing valuable insights for agricultural monitoring and disease management.

Implementation Steps :

1. Mounting the Google Drive in Google Colab and loading the dataset.
2. Importing the required libraries.
3. Displaying and resize the images.
4. Converting the images into NumPy arrays and scale the pixel values for normalization.
5. Analyzing class distribution and identify any class imbalance issues.
6. Partitioning the dataset into training, validation, and testing subsets.
7. Performing one-hot encoding on the target variable for classification.
8. Designing the model architecture, compile it, and train it using the training data.
9. Ploting the model’s accuracy and loss across epochs.
10. Generating predictions on the test data.
11. Displaying the actual and predicted labels for the test images.
12. Deploying the model using Streamlit for real-time use.
