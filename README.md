# Disaster Prediction using Natural Language Processing

## Overview
This project utilizes natural language processing (NLP) techniques to classify tweets as either related to natural disasters or not. The main goal is to create a model that accurately predicts whether a given tweet is discussing a disaster event or not.

## Introduction
Natural disasters, such as earthquakes, hurricanes, and wildfires, can have devastating effects on communities around the world. Man made distasters like invasions, reactor meltdowns, and chemical leaks can also have disasterous consequences. With the increasing use of social media, platforms like Twitter have become valuable sources of real-time information during such events. This project aims to leverage NLP techniques to automatically identify tweets that are relevant to disasters, enabling faster response and assistance efforts.

## Dataset
The dataset used for this project consists of a collection of tweets labeled as either "disaster" or "non-disaster". Each tweet is accompanied by its corresponding label, indicating whether it discusses a disaster event or not. The dataset is balanced to ensure equal representation of both classes.

## Approach
1. **Data Preprocessing**: The raw text data undergoes several preprocessing steps, including tokenization, lowercasing, removal of stop words, and stemming or lemmatization.
2. **Feature Extraction**: The preprocessed text is transformed into numerical features suitable for machine learning algorithms. 
3. **Model Training**: Various machine learning models using a neural network architecture are trained on the extracted features to classify tweets as disaster or non-disaster.
4. **Evaluation**: The trained models are evaluated using metrics such as accuracy, precision, recall, and F1-score to assess their performance in predicting tweet classifications.
