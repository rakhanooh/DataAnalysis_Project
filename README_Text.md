# Fake News Sentiment Analysis

## Project Overview
This project aims to build a model capable of predicting the authenticity of news articles by analyzing text data from the Fake News competition dataset. Using machine learning techniques, we explore methods to classify news articles as either *fake* or *real*, employing techniques in data preprocessing, feature extraction, and model training.


## 1. Introduction
The main objective is to classify news articles using a machine learning model. The dataset includes various features, including `title`, `author`, `text`, and a target `label` that marks an article as real or fake. This project is conducted as part of DS3114 under the guidance of Dr. Omaima A. Fallatah at Umm Al-Qura University.

## 2. Data Description
- id: Unique identifier for each news article.
- title: Title of the article.
- author: Author of the article.
- text: Main content of the article.
- label: Target label where `0` indicates real and `1` indicates fake.

## 3. Project Objectives
- Clean and preprocess the text data.
- Apply feature extraction methods, specifically Bag of Words (BoW) and TF-IDF.
- Train a Naive Bayes Multinomial model for classification.
- Evaluate and refine the model to optimize performance.

## 4. Data Exploration
We merged the three data files (train, test, and submit) into a single dataset called `fakenews` and removed unnecessary columns. This consolidation improved data organization and enabled focused analysis.
The dataset consists of 18,285 rows and 5 columns, with some missing values.

## 5. Data Preprocessing
Preprocessing steps include:
- Lowercasing text.
- Removing URLs, numbers, HTML tags, punctuation, whitespaces, emojis, mentions, and hashtags.
- Expanding contractions and tokenizing text.
- Lemmatizing tokens and removing common stopwords.
- Combining the `author` and `title` columns into a new feature for enhanced analysis.
-apply tokanizatin to (text )and steaming (content)

## 6. Model Implementation
### 6.1 Bag of Words
The Bag of Words approach was implemented first and performed well, capturing word frequency for classification purposes.

### 6.2 TF-IDF
TF-IDF, applied next, provided a more nuanced approach by adjusting word importance based on document frequency. However, BoW performed better for this dataset.

### 6.3 Naive Bayes Model
Both models were trained using the Naive Bayes Multinomial algorithm, with the BoW approach yielding the best results.

## 7. Conclusion
The project demonstrated the effectiveness of text preprocessing, feature extraction, and machine learning in fake news detection. While both BoW and TF-IDF proved useful, BoW was more suited for this dataset.
Challenges included handling missing labels in the test dataset, which were resolved through data consolidation.


#### Submited by 
Lamar Waleed Fattah

Rakha Mautq Nooh
