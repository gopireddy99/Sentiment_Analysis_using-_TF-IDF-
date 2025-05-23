# Sentiment_Analysis_using-_TF-IDF-

COMPANY - CODTECH IT SOLUTIONS

NAME - G.NITHISH KUMAR REDDY

INTERN ID - CT04DN40

DOMAIN - MACHINE LEARNING

DURATION - 4 WEEKS

MENTOR - NEELA SANTHOSH

📘 Project Title:
# Sentiment Analysis on Customer Reviews using TF-IDF Vectorization and Logistic Regression

📌 Project Description:
This project focuses on performing sentiment analysis on a large dataset of customer reviews. The goal is to automatically classify customer feedback into positive or negative sentiments using Natural Language Processing (NLP) techniques and machine learning. We utilize TF-IDF vectorization for feature extraction and Logistic Regression for classification.

💡 Objective:
To build a model that can understand the sentiment behind customer reviews by analyzing the text content, thereby providing insights into customer satisfaction and product perception.

📂 Dataset:
The dataset used in this project contains over 500,000 Amazon product reviews, each with a written review (Text) and a corresponding rating (Score) from 1 to 5.

Positive Reviews: Score of 4 or 5

Negative Reviews: Score of 1 or 2

Neutral Reviews (Score = 3) are discarded to simplify the classification problem into binary sentiment classification.

🔧 Steps Involved:
1. Data Cleaning and Preprocessing:
Removed neutral reviews.

Created binary sentiment labels: 1 for positive, 0 for negative.

Cleaned the text by:

Converting to lowercase

Removing URLs, numbers, and punctuation

2. Feature Extraction using TF-IDF:
Applied TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert the cleaned text data into numerical features.

Limited the number of features to 10,000 to reduce dimensionality and improve performance.

3. Model Training with Logistic Regression:
Trained a Logistic Regression model on the vectorized text.

Used an 80-20 train-test split for model evaluation.

4. Model Evaluation:
Evaluated the model using:

Accuracy Score

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix Visualization

The model achieved high accuracy and effectively distinguished between positive and negative reviews.

📊 Results:
The logistic regression classifier performed well, showing that even a simple linear model, when combined with good preprocessing and TF-IDF features, can achieve effective sentiment classification.

The confusion matrix and classification report provided insights into the performance, such as the number of true positives, false positives, etc.

