# Sentiment NLP Analysis Project

## Overview
This Jupyter notebook demonstrates a sentiment analysis project using Natural Language Processing (NLP) techniques. The project focuses on classifying text sentiments into categories like **joy** and **sad** using machine learning approaches.

## Key Components
- **Libraries Used**: 
  - pandas
  - numpy
  - matplotlib
  - scikit-learn
  - NLTK

## Dataset Characteristics
The dataset contains text samples with corresponding sentiment labels:
- Columns: Unnamed index, sentiment, text
- Sample entries include:
  - Texts about social issues
  - Emotional expressions
  - COVID-19 related comments

## Performance Metrics
The model's performance was evaluated across different feature vector lengths, showing:
- **Increasing Accuracy**: From 0.526 to 0.667
- **Metrics Tracked**:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

## Key Observations
- Best performance achieved with feature vector lengths around **2000-3000**
- Consistent improvement in model performance as feature vector length increases
- Final model reaches approximately **66.7% accuracy**
