# Sentiment_Analysis

Trying to utilize the winter break by doing something useful. :)

Predicting the reviews sentiments and IMDb ratings for Movies using LSTM for IMDB Movie Reviews dataset having 50,000 reviews.
Three separate neural networks have been used in the project- CNN, LSTM, and a simple Neural Network.

Following is the summary of what has been done:
* Load the IMDb Movie Reviews dataset (50,000 reviews)
* Pre-process dataset by removing special characters, numbers, etc. from user reviews + convert sentiment labels positive & negative to numbers 1 & 0, respectively
* Import GloVe Word Embedding to build Embedding Dictionary + Use this to build Embedding Matrix for our Corpus
* Model Training using Deep Learning in Keras for separate: Simple Neural Net, CNN and LSTM Models and analyse model performance and results
* Last, perform predictions on real IMDb movie reviews

