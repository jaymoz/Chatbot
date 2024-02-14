# Transformer-based Chatbot using PyTorch

## Overview
A custom-built chatbot leveraging a transformer architecture, implemented from scratch using PyTorch. The model is trained on the Cornell Movie-Dialogs Corpus, with an emphasis on handling conversational data and generating coherent responses.

## Features
- **Custom Transformer Architecture**: Implements a multi-head attention mechanism, positional encodings, and feed-forward networks within the transformer architecture.
- **Data Preprocessing**: Includes functions for parsing, cleaning, and encoding conversational data from movie scripts.
- **Dynamic Masking**: Utilizes masks for the transformer model, allowing for efficient training and prediction.
- **Loss Function with Label Smoothing**: Implements a Kullback-Leibler Divergence loss function with label smoothing for better generalization.

## Requirements
- Python 3.x
- PyTorch
- CUDA (Optional for GPU acceleration)

## Usage
1. **Data Processing**: The `DataProcessing` class handles parsing and preparing data.
2. **Model Training**: Train the model using the defined transformer architecture and data loaders.
3. **Evaluation**: The trained model can be used for generating responses to new inputs.

## Implementation Details
- **Data Processing**: Converts text data into tokenized pairs and creates a word map for vocabulary.
- **Transformer Model**: Includes encoder and decoder layers with multi-head attention and feed-forward networks.
- **Training Routine**: Incorporates an Adam optimizer with warm-up steps and a custom loss function.

## Example Usage
After training, the model can interactively generate replies to user inputs in a command-line interface.


