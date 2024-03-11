# Land-use-identification
This project uses transfer learning for classifying satellite imagery by land use

# Transfer Learning for Land Use Classification README

## Overview
This project harnesses the power of transfer learning to classify satellite imagery into distinct urban land use categories, including single-family residential, multi-family residential, commercial, industrial, and open space. Utilizing a pre-trained feature extractor from TensorFlow Hub combined with a custom densely connected neural network, the model aims at accurately recognizing and categorizing land use types from high-resolution images. The approach demonstrates significant potential for applications in urban planning and environmental monitoring.

## Model Framework
- **Data Preprocessing**: Employs TensorFlow to load, preprocess, and augment satellite images to optimize them for the classification task.
- **Transfer Learning Core**: Leverages a pre-trained model from TensorFlow Hub, such as ResNet, as a foundational feature extractor, enhancing the model's learning efficiency and accuracy with limited dataset sizes.
- **Custom Evaluation Metrics**: Features macro F1-score among other metrics for a comprehensive evaluation, particularly beneficial for assessing performance in imbalanced class scenarios.
- **Training Progress Visualization**: Uses Matplotlib to offer insights into the model's training dynamics, showcasing metrics such as loss reduction and F1-score enhancements.
