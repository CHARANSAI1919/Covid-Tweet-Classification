# Covid-Tweet-Classification

During the COVID-19 pandemic, social media platforms like Twitter became a primary source for public discourse, spreading both factual information and emotional responses. However, distinguishing between COVID-19-related and non-COVID-19 tweets while further classifying them based on emotions is essential for understanding public sentiment and misinformation trends. 

## Objectives

This project aims to develop a hierarchical classification system for tweets, addressing the following objectives:

### 1. First-Level Classification
- Categorize tweets into Corona-related and Non-Corona-related based on content.

### 2. Second-Level Classification
- Further classify Corona-related tweets into:
  - Emotional tweets (expressing fear, sadness, hope, anger, etc.).
  - Non-emotional tweets (informational or factual updates).
- Further classify Non-Corona tweets into:
  - Emotional tweets (general emotions unrelated to COVID-19).
  - Non-emotional tweets (neutral or generic discussions).

### 3: Emotion Categorization 
- Classify emotional tweets into six primary emotion categories: 
 - Anger 
 - Disgust 
 - Fear 
 - Happiness 
 - Surprise 
 - Sadness
   
### 4: Sadness → Depression vs. Non-Depression Classification 
- Further classify sadness-related tweets into: 
 -  Depression-related tweets (tweets indicating severe distress, hopelessness, 
suicidal tendencies). 
 - Non-depression sadness tweets (general sadness, disappointment, grief).

## Dataset Labelling

Below diagram represents the labelling of the dataset for the hackathon:

![Screenshot 2025-02-07 140429](https://github.com/user-attachments/assets/3e0c9dd7-5238-4ac8-9a51-25e8cb21cfa7)
