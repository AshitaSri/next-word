# Next Word Predictor Using LSTM

A deep learning project that predicts the next word in a sequence using Long Short-Term Memory (LSTM) neural networks.

## Overview

This project implements a next-word prediction system similar to smartphone keyboard suggestions and Gmail's Smart Compose feature. It uses LSTM to learn patterns in text and predict the most likely next word given a sequence of input words.

## Technical Details

### Architecture
- Uses LSTM (Long Short-Term Memory) neural networks
- Converts text generation into a supervised learning problem
- Implements word tokenization using Keras Tokenizer

### Data Processing
1. Text is split into sentences
2. Words are converted to numerical tokens
3. Input-output pairs are created from sequential words
   - Input: Sequence of words
   - Output: Next word in sequence

### Dependencies
- TensorFlow
- Keras
- Python 3.x

## Use Cases
- Smart keyboard suggestions
- Text completion systems
- Code completion tools
- Writing assistance

## Historical Note
This approach was initially used by SwiftKey for their keyboard prediction system before moving to more complex models.

## Dataset
For demonstration purposes, the project uses a small FAQ dataset. For production use, a larger dataset would be recommended for better prediction accuracy.
