# bert-sentiment-analysis
Sentiment analysis of text reviews using BERT transformer model implemented in PyTorch.

This project demonstrates how to fine-tune a pre-trained BERT model for sentiment classification on a text review dataset. It covers the full pipeline including:

Data loading and preprocessing (text cleaning, tokenization, and encoding)

Mapping sentiment labels and dataset splitting with stratification

Defining a custom PyTorch Dataset class for efficient batching

Model architecture setup with dropout and linear classification layer on top of BERT

Training with AdamW optimizer and learning rate scheduling

Model evaluation using accuracy, loss, and confusion matrix visualization

Making predictions on new text samples with probability scores

Saving and loading the trained model for reuse

This notebook is designed for intermediate users familiar with PyTorch and transformers, and it can be adapted to other text classification tasks.
