# AI_ML_1_Cats_vs_Dogs_BYTE# Cats vs Dogs Image Classification

## Objective
Build a deep learning image classification model that can distinguish between cats and dogs.

## Dataset
Microsoft Cats and Dogs Dataset.

## Preprocessing
- Removed corrupted images
- Resized images to 150x150 pixels
- Used an 80/20 training-validation split
- Pixel values were normalized to 0-1

## Model
A Convolutional Neural Network (CNN) was developed using TensorFlow/Keras.

The model includes:
- Rescaling layer
- 3 Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layer
- Dropout
- Sigmoid output layer

## Training
The model was trained for 10 epochs using:
- Optimizer: Adam
- Loss: Binary Crossentropy
- Batch size: 32

## Results
Test accuracy: [YOUR TEST ACCURACY HERE]

## Evaluation
The project includes:
- Training/validation accuracy graph
- Training/validation loss graph
- Confusion matrix
- Classification report
- 10 sample predictions with ground-truth labels

## Model File
The trained model is provided as:

`cats_vs_dogs_model.keras`

## Inference
The saved model can be loaded using TensorFlow/Keras and used to classify new cat and dog images.
