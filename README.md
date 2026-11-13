# Movie Review Sentiment Analysis

Classifies IMDB movie reviews as positive or negative using an LSTM neural network.

## Dataset
IMDB 50K Movie Reviews from Kaggle (lakshmi25npathi/imdb-dataset-of-50k-movie-reviews): 50,000 reviews, 25,000 positive and 25,000 negative.

## Tools
Python, Pandas, TensorFlow/Keras, scikit-learn

## Method
1. Encoded labels and split the data 80/20 (40,000 train, 10,000 test)
2. Tokenized the text and padded reviews to 200 tokens
3. Trained an LSTM model for 10 epochs
4. Evaluated on the test set

## Results
Test accuracy: 89.2%

## How to run
Download the dataset from Kaggle, put IMDB Dataset.csv next to the notebook, and run all cells in Google Colab or Jupyter.
