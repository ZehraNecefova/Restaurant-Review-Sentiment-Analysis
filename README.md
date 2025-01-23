# Restaurant-Review-Sentiment-Analysis
This project involves analyzing restaurant reviews to classify customer sentiments as positive or negative using machine learning. The goal is to preprocess textual data and train a model to predict sentiments effectively based on the reviews.

Key Features:
Text Preprocessing:
Cleans and normalizes text by removing special characters, converting to lowercase, removing stopwords, and applying stemming.

Feature Extraction:
Converts the processed text into numerical format using Bag-of-Words (BoW) representation with CountVectorizer.

Machine Learning Model:
Implements a Naive Bayes Classifier for sentiment classification.

Evaluation:
Assesses model performance using accuracy, confusion matrix, precision, recall, and F1-score.

Project Workflow:
Data Cleaning:
Reads and preprocesses the dataset by removing special characters, stopwords, and applying stemming to standardize the text.

Feature Engineering:
Uses Bag-of-Words (BoW) with a maximum of 1,500 features to represent text numerically.

Train-Test Split:
Splits the data into training (80%) and testing (20%) subsets.

Model Training:
Trains a Naive Bayes Classifier on the processed training data.

Evaluation:
Tests the model on unseen test data and evaluates it using:
Accuracy, Confusion Matrix and Classification Report.
