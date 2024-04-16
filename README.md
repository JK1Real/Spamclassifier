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
