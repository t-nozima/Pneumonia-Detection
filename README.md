# Pneumonia Detection from Chest X-Ray Images

## Project Overview

This project aims to develop an image classification model to detect pneumonia from pediatric chest X-ray images. The dataset is sourced from the [Kaggle Pneumonia Detection Competition](https://www.kaggle.com/competitions/pnevmoniya/overview), containing images of healthy lungs and lungs infected with pneumonia.
The goal is to build an accurate and efficient deep learning model that can assist in early and reliable detection of pneumonia.

## Dataset

* __Source__: [Kaggle Pneumonia Dataset](https://www.kaggle.com/competitions/pnevmoniya/data)
* __Content__: Chest X-ray images labeled as either NORMAL or PNEUMONIA

## Approach

__1. Data Preparation:__

* Verified and cleaned image data.
* Split data into training and validation sets (80% train, 20% validation).
* Resized images to 224x224 for model compatibility.

__2. Model Building:__

* Used a pre-trained ResNet34 convolutional neural network.
* Fine-tuned the model with fastai’s high-level API.

__3. Evaluation:__

* Achieved __98.66% accuracy__.

__4. Predictions:__

* __1__: Pneumonia

* __0__: Normal

## Tech Stack

* Python
* PyTorch & FastAI
* Pandas & NumPy
* OpenCV
* Matplotlib & Seaborn

## Results

* __Accuracy__: 98.66%

* __Confusion Matrix__:

![confusion matrix](https://github.com/user-attachments/assets/a9ea11c1-bcb5-4826-9160-c4ec1ed7ff7d)
