# Sentiment_Analysis
This repository contains the implementation and analysis of sentiment analysis on the IMDB dataset using Recurrent Neural Networks (RNNs).

## Project Overview
Preprocessed the IMDB dataset by padding sequences to a uniform length of 800, handling 50,000 movie reviews.
Conducted Exploratory Data Analysis (EDA) on word frequencies and review lengths (11 to 2494 words), and created a word-index mapping for text processing.
Engineered and implemented four types of Recurrent Neural Network (RNN) models: SimpleRNN, GRU, LSTM, and BiLSTM.
Utilized Embedding layers to transform input words into 64-dimensional vectors, optimizing RNN model performance.
Trained models using 70% of the dataset over 10 epochs, with a 30% validation split to monitor performance.
Achieved high accuracy on test data: SimpleRNN (70.8%), GRU (85.6%), LSTM (84%), BiLSTM (85%).
## Model Architectures
SimpleRNN: Basic RNN architecture.
GRU (Gated Recurrent Unit): Improved RNN variant.
LSTM (Long Short-Term Memory): Another popular RNN variant known for handling long-range dependencies.
BiLSTM (Bidirectional LSTM): LSTM variant that processes input in both forward and backward directions.
