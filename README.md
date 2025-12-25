# Next Word Prediction LSTM 

This project processes the full text of *The Adventures of Sherlock Holmes* by Arthur Conan Doyle for language modeling tasks. It tokenizes the text, creates word indices, and generates input sequences suitable for next-word prediction models using TensorFlow and Keras.

## Features

- Reads plain text file (`data.txt`) containing the book.
- Tokenizes the text into word indices using Keras `Tokenizer`.
- Generates sequences for next-word prediction.
- Prepares padded sequences and one-hot encoded targets ready for training an LSTM/GRU model.
- Memory-efficient processing for large datasets.

## Installation

```bash
git clone <your-repo-url>
cd <your-repo-folder>
pip install tensorflow numpy
