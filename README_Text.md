# Fake News Sentiment Analysis

## Project Overview
This project aims to build a model capable of predicting the authenticity of news articles by analyzing text data from the Fake News competition dataset. Using machine learning techniques, we explore methods to classify news articles as either *fake* or *real*, employing techniques in data preprocessing, feature extraction, and model training.


##  Introduction
The main objective is to classify news articles using a machine learning model. The dataset includes various features, including `title`, `author`, `text`, and a target `label` that marks an article as real or fake. This project is conducted as part of DS3114 under the guidance of Dr. Omaima A. Fallatah at Umm Al-Qura University.

##  Data Description
- id: Unique identifier for each news article.
- title: Title of the article.
- author: Author of the article.
- text: Main content of the article.
- label: Target label where `0` indicates real and `1` indicates fake.

##  Project Objectives
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
- Apply tokanizatin to (text )and steaming (content)

##  Model Implementation
###  Bag of Words
The Bag of Words approach was implemented first and performed well, capturing word frequency for classification purposes.

###  TF-IDF
TF-IDF, applied next, provided a more nuanced approach by adjusting word importance based on document frequency. However, BoW performed better for this dataset.

###  Naive Bayes Model
Both models were trained using the Naive Bayes Multinomial algorithm, with the BoW approach yielding the best results.

## Usage
Load and Explore the Data: Import the dataset, perform initial data exploration and preprocessing.
Data Preprocessing: Apply tokanizatin to (text )and steaming (content) ,Lemmatizing tokens and removing common stopwords.
Model Training and Evaluation: Train the Naive Bayes and Random Forest models, then evaluate using accuracy and F1-score.
Comparison of Results: Review model performance to select the optimal algorithm for diabetes prediction.

##  Conclusion
The project demonstrated the effectiveness of text preprocessing, feature extraction, and machine learning in fake news detection. While both BoW and TF-IDF proved useful, BoW was more suited for this dataset.
Challenges included handling missing labels in the test dataset, which were resolved through data consolidation.


#### Submited by 
Lamar Waleed Fattah

Rakha Mautq Nooh
