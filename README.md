# youtube-comment-sentiment-emotion-analysis
This repository contains the presentation for a group project exploring sentiment and emotion patterns in YouTube comments using modern NLP techniques.

## Project Overview
Traditional engagement metrics such as views and likes provide only limited insight into how audiences actually feel about online content. This project investigates how sentiment and emotional responses are expressed in YouTube comments and how these reactions evolve over time.

The analysis focuses on identifying sentiment polarity and emotional categories in comment text using transformer-based models.

## Research Questions
- How are sentiments and emotions distributed within YouTube comments?
- What temporal patterns can be observed in audience reactions across different timeframes (daily, weekly, monthly)?
- What challenges arise when analyzing social media text data for sentiment and emotion detection?

## Methods
The project applied Natural Language Processing techniques using pre-trained transformer models:

- **Sentiment analysis:** `twitter-roberta-base-sentiment-latest`
- **Emotion detection:** `roberta-base-go_emotions`

These models allow classification of text into sentiment categories (positive, neutral, negative) and multiple emotional labels derived from the GoEmotions dataset.

The workflow included:
- collecting YouTube comments
- cleaning and preprocessing text
- applying transformer-based classification models
- analyzing the distribution of sentiment and emotional categories
- visualizing results in an interactive dashboard environment.

## Challenges
Social media data presents several challenges for NLP analysis, including:

- sarcasm and irony
- informal language and slang
- multilingual comments
- context-dependent meaning

## Limitations
- Analysis focused only on English-language comments
- Social media language evolves quickly, which may affect model accuracy
- Computational resources can limit large-scale analysis.

## Project Context
This project was developed as part of a university course (Computational Knowledge Analysis) during the MA in Data and Discourse Studies at Technische Universität Darmstadt.

## Repository Contents
- `CKA Presentation-Group 3.pptx` — project presentation

## Authors
- Mohammed Moussaoui  
- Moudy Letifa Azizah  
- Abdelkarim Zirar  
