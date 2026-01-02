# Sentiment Analysis using RNN and LSTM (PyTorch)

This project implements a **binary sentiment analysis system** using both **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)** models built with PyTorch. Text reviews are preprocessed, tokenized, and converted into numerical sequences, which are then passed through embedding layers and sequence models to classify sentiments as **positive or negative**.

---

## Features
- Text preprocessing and cleaning
- Tokenization and vocabulary encoding
- Sequence padding and length-aware batching
- Word embedding layer
- Vanilla RNN and LSTM models
- Dropout for regularization
- Binary sentiment classification
- Reproducible training with fixed random seeds

---

## Model Architectures

### RNN
- Embedding Layer  
- Multi-layer RNN  
- Dropout  
- Fully Connected Layer  
- Sigmoid Activation  

### LSTM
- Embedding Layer  
- Multi-layer LSTM (captures long-term dependencies)  
- Dropout  
- Fully Connected Layer  
- Sigmoid Activation  

Only the **final time-step output** is used for sentiment prediction.

---

## Project Structure
Sentiment_Analysis.ipynb

## Thank you note
Thank you for checking out this repository. Feel free to connect for improvements and contributions.
