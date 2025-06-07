# IMDB-sentiment-
A Python-based IMDB sentiment analysis project using TF-IDF feature extraction and Logistic Regression to classify movie reviews as positive or negative.

IMDB Sentiment Analysis

This Jupyter notebook performs binary sentiment classification on 50,000 IMDB movie reviews using a TF-IDF + Logistic Regression pipeline. It:
	•	Data Cleaning: Strips HTML tags, lowercases text, removes punctuation and stopwords.
	•	Train/Validation/Test Split: Uses stratified splits to ensure balanced classes.
	•	TF-IDF Vectorization: Converts each review into a 10,000-dimensional feature vector of unigrams and bigrams.
	•	Model Training: Trains a Logistic Regression classifier and evaluates performance through accuracy, precision/recall/F1, and a confusion matrix.
	•	Visualization: Generates word clouds and review-length histograms for exploratory analysis.
