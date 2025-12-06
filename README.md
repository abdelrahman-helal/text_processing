# Text Processing - Machine Learning Project

This repository contains machine learning models for text classification and topic clustering using Telegram message data.

## Overview

This project explores text classification techniques to identify message senders from Telegram chat data. The work includes:

1. **Naive Bayes Classification**: Initial approach using Naive Bayes to classify messages by sender, with handling for class imbalance
2. **BERT Fine-tuning**: Fine-tuned BERT model for sender classification
3. **Topic Clustering**: Clustering analysis on both TF-IDF and BERT-encoded vectors to identify themes in conversations

## Data

The project uses Telegram message exports in JSON format. Messages are cleaned by:
- Removing emojis and Unicode symbols
- Filtering for text-only messages (excluding links, media, files)
- Processing text entities

## Requirements

Key dependencies include:
- `scikit-learn`
- `sentence-transformers`
- `pandas`
- `numpy`
- `matplotlib`
- `transformers` (for BERT)

## Note

This project was developed as part of CS156 coursework. Message data was used with consent from all participants.

