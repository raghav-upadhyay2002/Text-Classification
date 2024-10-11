# Hate Speech Detection Model

This project focuses on developing a machine learning model to detect and classify hate speech in online text. Using a dataset sourced from Kaggle, the model aims to enhance content moderation on social media platforms and create a safer online environment.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Dataset

The dataset used in this project contains approximately 56,745 text samples, each labeled as either hate speech or non-hate speech. It includes a variety of topics, ensuring a comprehensive set of training examples. The data is split into two parts:
- **Imbalanced Dataset**: 31,962 samples focused on identifying hate speech.
- **Raw Dataset**: 24,783 samples covering hate speech, abusive language, and non-hate speech.

Data preprocessing steps included removing irrelevant columns, adjusting labels for consistency, and merging the two datasets to create a well-rounded dataset for model training.

## Installation

To run this project, you will need Python installed on your machine along with the following packages:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
