# Spam Classifier

This project aims to classify emails or SMS messages as either spam or not spam using machine learning techniques.

## Overview

This repository contains code for a spam classifier implemented using Python and Streamlit. The classifier utilizes a Multinomial Naive Bayes model trained on a dataset of labeled messages.

## Features

- Text preprocessing: The input messages are preprocessed to remove stopwords, punctuation, and are stemmed for better classification accuracy.
- Vectorization: The preprocessed messages are vectorized using TF-IDF (Term Frequency-Inverse Document Frequency).
- Model Prediction: The vectorized input is fed into the trained Multinomial Naive Bayes model for prediction.
- Streamlit App: The classifier is deployed using Streamlit, providing a user-friendly interface for users to input messages and receive classification results.

## Installation

1. Clone this repository:
```bash
   git clone https://github.com/JK1Real/Spamclassifier.git
```

## Usage

1. Navigate to the project directory.
2. Run the Streamlit app:  streamlit run app.py
3. Input a message into the provided text field.
4. Click the "predict" button to classify the message as "spam" or "not spam".

## Model Training

The Multinomial Naive Bayes model is trained using the `model_building.ipynb` notebook. It involves the following steps:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Text preprocessing: tokenization, removing stopwords, punctuation, and stemming
- Model building and evaluation

## Files

- `app.py`: Streamlit app for the spam classifier.
- `model_building.ipynb`: Jupyter notebook containing code for data preprocessing, model training, and evaluation.
- `vectorizer.pk1`: Pickled TF-IDF vectorizer.
- `model.pk1`: Pickled Multinomial Naive Bayes model.
- `spam.csv`: Dataset containing labeled messages for training and testing.

