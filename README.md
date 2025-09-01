Sentiment Analysis on IMDB Reviews using LSTM and Keras
This project implements a Sentiment Analysis model using LSTM (Long Short-Term Memory) networks with Keras to classify IMDB movie reviews as positive or negative.

📋 Project Overview
Sentiment Analysis is a natural language processing (NLP) task that involves classifying text into emotional categories. In this project, we use deep learning to classify IMDB movie reviews into positive or negative sentiments using an LSTM-based neural network architecture.

🏗️ Architecture
The model architecture consists of the following layers:

Embedding Layer - Converts words into dense vectors of fixed size

LSTM Layer - Processes the sequence data and captures long-term dependencies

Dense Layer - Output layer with sigmoid activation for binary classification

Training Configuration:

Optimizer: Adam

Loss Function: Binary Crossentropy

Metrics: Accuracy

📊 Dataset
The model is trained on the IMDB Dataset of 50K Movie Reviews from Kaggle(https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

Dataset Characteristics:

50,000 movie reviews

Balanced dataset (25,000 positive + 25,000 negative reviews)

Two columns: review text and sentiment label
