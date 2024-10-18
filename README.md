# Hand Gesture Recognition using CNN

This project is focused on building a hand gesture recognition model using the dataset from Kaggle. The dataset consists of infrared images representing different hand gestures performed by 10 subjects. We use Convolutional Neural Networks (CNN) to classify these gestures.

# The main steps in this project are:

  1. Data Loading and Preprocessing
  2. CNN Model Construction
  3. Training the Model
  4. Evaluating Performance
  5. Making Predictions and Visualizing Results

# Model Architecture

The CNN used in this project consists of:
  1. 3 Convolutional layers with 32, 64, and 128 filters respectively, followed by MaxPooling layers.
  2. A fully connected Dense layer with 128 units, followed by a Dropout layer to prevent overfitting.
  3. A final Dense layer with softmax activation for multi-class classification (10 gestures).

# Results

The model achieved the following results after 3 epochs:
  1. Training Accuracy: 99.23%
  2. Validation Accuracy: 99.87%
  3. Test Accuracy: 99.85%
  4. The model shows excellent performance on both training and test data, making it highly accurate for hand gesture recognition.
