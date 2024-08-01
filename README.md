# Satellite Image Classification

This project focuses on classifying satellite images into different land cover categories using deep learning models.

## Project Overview

The main objective of this project is to develop and evaluate machine learning models that can accurately classify satellite images into predefined classes such as:
- Cloudy
- Desert
- Green Area
- Water

## Models Used

The project implements and compares multiple state-of-the-art deep learning models:
- **ResNet-50**
- **EfficientNetB2**
- **MobileNetV2**

## Project Workflow

1. **Data Preparation**:
   - Data is loaded and preprocessed from the dataset directory.
   - Images are categorized into the aforementioned classes.

2. **Model Training**:
   - Models are trained on the dataset with an 80-10-10 split for training, validation, and testing respectively.
   - Multiple epochs are used to ensure the models learn effectively.

3. **Evaluation**:
   - The models are evaluated on the validation and test sets to assess their accuracy and performance.
   - The best performing model is selected based on validation accuracy.

## Results

The MobileNetV2 model achieved an accuracy of 96.27% on the validation dataset.

## Requirements

- TensorFlow
- NumPy
- Matplotlib
- Pandas

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter notebook file to train and evaluate the models.

