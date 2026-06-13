# Plant Disease Detection using Deep Learning

## Overview
This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify plant diseases from leaf images. The model helps identify crop diseases automatically, enabling early diagnosis and better agricultural decision-making.

## Features
- Multi-class plant disease classification
- Trained on 38 disease and healthy plant categories
- Image preprocessing and augmentation support
- Model checkpointing for best-performing model
- Prediction on new leaf images

## Tech Stack
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Dataset
New Plant Diseases Dataset (Augmented)

- Source: Kaggle
- Training Images: 70,295
- Validation Images: 17,572
- Classes: 38

## Model Architecture
- Rescaling Layer
- Conv2D + MaxPooling2D
- Conv2D + MaxPooling2D
- Conv2D + MaxPooling2D
- Flatten Layer
- Dense Layer (512 neurons)
- Output Layer (38 classes, Softmax)

## Results
- Best Validation Accuracy: 94.44%
- Final Training Accuracy: 98.37%

## Sample Prediction
The trained model can classify uploaded leaf images and predict the most likely disease category with confidence scores.

## Future Improvements
- Mobile application integration
- Transfer learning using EfficientNet or ResNet
- Real-time disease detection
- Disease treatment recommendations
