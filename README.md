# Sentiment_Analysis
This repository contains the implementation and analysis of sentiment analysis on the IMDB dataset using Recurrent Neural Networks (RNNs).

## Project Overview
<ul>Preprocessed the IMDB dataset by padding sequences to a uniform length of 800, handling 50,000 movie reviews.</ul>
<ul>Conducted Exploratory Data Analysis (EDA) on word frequencies and review lengths (11 to 2494 words), and created a word-index mapping for text processing.</ul>
<ul>Engineered and implemented four types of Recurrent Neural Network (RNN) models: SimpleRNN, GRU, LSTM, and BiLSTM.</ul>
<ul>Utilized Embedding layers to transform input words into 64-dimensional vectors, optimizing RNN model performance.</ul>
<ul>Trained models using 70% of the dataset over 10 epochs, with a 30% validation split to monitor performance.</ul>
<ul>Achieved high accuracy on test data: SimpleRNN (70.8%), GRU (85.6%), LSTM (84%), BiLSTM (85%).</ul>
## Model Architectures
<li>SimpleRNN: Basic RNN architecture.</li>
<li>GRU (Gated Recurrent Unit): Improved RNN variant.</li>
<li>LSTM (Long Short-Term Memory): Another popular RNN variant known for handling long-range dependencies.</li>
<li>BiLSTM (Bidirectional LSTM): LSTM variant that processes input in both forward and backward directions.</li>
