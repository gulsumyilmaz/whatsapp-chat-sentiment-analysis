# WhatsApp Chat Sentiment Analysis

This project analyzes WhatsApp chat messages and classifies them into positive and negative sentiment using Natural Language Processing (NLP) and machine learning techniques.

## Problem Statement
Messaging platforms generate large volumes of unstructured text data. 
The goal of this project is to extract sentiment insights from WhatsApp chat messages by building an end-to-end NLP pipeline.

## Dataset
The dataset consists of exported WhatsApp chat messages with the following fields:
- user
- message
- year, month, day, hour, minute

Media messages and non-text content are removed during preprocessing.

## Approach
- Data cleaning and filtering
- Text preprocessing and normalization
- Weakly supervised sentiment labeling using lexicon-based methods
- Feature extraction using TF-IDF
- Binary sentiment classification using Logistic Regression

## Technologies Used
- Python
- Pandas, NumPy
- TextBlob
- Scikit-learn
- TF-IDF Vectorization

## Results
The model demonstrates reasonable performance given the noisy and weakly-labeled nature of chat data.
Evaluation is performed using standard classification metrics.

## Key Learnings
- Handling real-world unstructured text data
- Building an end-to-end NLP pipeline
- Applying weakly supervised learning techniques
- Feature extraction and model evaluation for text classification

## Future Improvements
- Replace lexicon-based labeling with human-labeled data
- Experiment with advanced NLP models (e.g., transformers)
- Deploy the model as an API
