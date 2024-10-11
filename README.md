# Hate Speech Detection Model

This project focuses on developing a machine learning model to detect and classify hate speech in online text. Using a dataset sourced from Kaggle, the model aims to enhance content moderation on social media platforms and create a safer online environment.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training](#model-training)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Dataset

The dataset used in this project contains approximately 56,745 text samples, each labeled as either hate speech or non-hate speech. It includes a variety of topics, ensuring a comprehensive set of training examples. The data is split into two parts:
- **Imbalanced Dataset**: 31,962 samples focused on identifying hate speech.
- **Raw Dataset**: 24,783 samples covering hate speech, abusive language, and non-hate speech.
## Installation
Install the required libraries:
```bash
pip install -r requirements.txt
```

Data preprocessing steps included removing irrelevant columns, adjusting labels for consistency, and merging the two datasets to create a well-rounded dataset for model training.
## Model Training

The model was developed using a neural network architecture. During training, the model achieved an accuracy of 93.51% on the test data, indicating its effectiveness in identifying hate speech.
   
## Results

The trained model demonstrates that machine learning techniques can automate the identification of hate speech, thereby improving safety on social media platforms.

## Acknowledgements
1. The dataset was sourced from Kaggle.
2. Thank you to the developers and researchers who created the datasets and the open-source community for providing valuable tools and libraries.

   
