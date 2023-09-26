## Introduction

Skin disease diagnosis is a crucial task in healthcare, and leveraging artificial intelligence models can aid in the early detection of various skin conditions. This web application allows users to upload skin images and obtain predictions about the type of skin disease present.

The application offers multiple deep learning models for predictions, including Xception, EfficientNetB5, and VGG19. Users can choose a model based on their preferences and assess the model's performance with classification reports and confusion matrices.

## Features

- Skin disease classification based on input images.
- Multiple deep learning models to choose from (Xception, EfficientNetB5, VGG19).
- Top 5 predictions to assess classification uncertainty.
- Classification reports and confusion matrices for model evaluation.

## Installation

1. Clone the repository:

git clone https://github.com/amr-elnadi-007/the-app-2


2. Install the required dependencies:
pip install -r requirements.txt

3. Run the Streamlit web application:
streamlit run app.py



Usage
Access the web application by running it using Streamlit.
Upload a skin image for classification.
Select a model from the dropdown menu (Xception, EfficientNetB5, or VGG19).
Click the "Predict" button to obtain disease classification.
View the top predictions, classification report, and confusion matrix for model evaluation.


The application includes the following pre-trained deep learning models:

Xception: A deep convolutional neural network known for its strong feature extraction capabilities.
EfficientNetB5: An efficient and effective model for image classification tasks.
VGG19: A well-established model with deep layers for image classification.
You can choose the model that best suits your needs when making predictions.


Data

The skin disease classification models were trained on the augmented version of the ISIC 2019 dataset, consisting of approximately 89,000 skin images across 8 different classes. The dataset was balanced to ensure fair representation of each class during training.
