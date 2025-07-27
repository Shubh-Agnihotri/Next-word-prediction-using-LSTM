# Next-word-prediction-using-LSTM
This project builds a Next Word Prediction model using an LSTM in PyTorch. It tokenizes text, learns word sequences, and predicts the next word based on context, showcasing how LSTMs capture language patterns for text generation and autocomplete tasks.

# Next Word Prediction using LSTM

## 📌 Project Overview
This project implements a **Next Word Prediction** model using an **LSTM (Long Short-Term Memory)** network built with PyTorch. The model learns word dependencies from text data and predicts the next word given a sequence of words. This demonstrates the use of deep learning for NLP tasks like text generation and autocomplete.

## 🚀 Features
- Text preprocessing and tokenization using **NLTK**
- Vocabulary creation and input-output sequence generation
- LSTM-based neural network for sequential word learning
- Training and prediction pipeline implemented in **PyTorch**

## 🛠️ Technologies Used
- Python
- PyTorch
- NLTK
- NumPy

**LSTM Model**
- The model includes:
  - An Embedding Layer to convert word indices into dense vectors.
  - An LSTM Layer to capture temporal relationships.
  - A Fully Connected Layer to predict the next word.

## 🚀 **Training Loop**
- Loss is computed using `nn.CrossEntropyLoss`.
- The optimizer (`Adam`) updates the model parameters.
- Training progress is logged after each epoch.

## 📌 **Prediction Function**
- A function takes an input phrase and predicts the next word using the trained model.
- It converts words to indices, runs the model, and outputs the predicted word.
