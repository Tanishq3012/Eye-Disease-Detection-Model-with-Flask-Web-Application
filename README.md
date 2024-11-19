# Eye Disease Detection Model

This repository contains an image detection model for testing eye diseases, including cataract, diabetic retinopathy, glaucoma, and normal eyes. The model was built using BERT and TensorFlow, with all model training, testing, and visualization included. The model's performance is integrated into a Flask-based web application for user interaction.

## Table of Contents
- [Overview](#overview)
- [Model Details](#model-details)
- [Dataset](#dataset)
- [Results](#results)
- [Website](#website)
- [Installation](#installation)


## Overview
This project aims to detect four types of eye conditions using an image classification model:
1. Cataract
2. Diabetic Retinopathy
3. Glaucoma
4. Normal

## Model Details
- **Model/Frameworks Used**: BERT, TensorFlow
- **Model Training**: The model was trained on a dataset of labeled eye disease images.
- **Performance Metrics**:
  - Cataract: 93.50%
  - Diabetic Retinopathy: 99.29%
  - Glaucoma: 72.27%
  - Normal: 79.70%

## Dataset
The dataset used for training and testing consists of labeled images for each of the four categories. Data visualization and class-level accuracy metrics are provided in the `https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification`.

## Results
The results of the model include accuracy metrics for each class:
- **Cataract**: 93.50%
- **Diabetic Retinopathy**: 99.29%
- **Glaucoma**: 72.27%
- **Normal**: 79.70%

## Website
A Flask-based web application is integrated with the trained model. Users can upload an image of an eye, and the model will predict the condition. The web app is located in the `app.py` file.

## Installation
To set up the project locally:
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/eye-disease-detection.git
   cd eye-disease-detection
2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. Install the required packages:
   ```sh
   cd webapp
   python app.py
