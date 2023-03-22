# NLP Model for Disaster Tweets
This Jupyter Notebook demonstrates how to build a natural language processing (NLP) model using TensorFlow to predict if a tweet is about a real disaster or not. The dataset used in this notebook is the Disaster Tweets dataset from Kaggle.

Requirements
To run this notebook, you will need:
- jupyter notebbok

# Data Preparation
The Disaster Tweets dataset contains 7,613 training samples and 3,263 test samples. Each sample consists of a tweet and a label indicating whether the tweet is about a real disaster or not. The dataset is preprocessed using NLTK to tokenize the words and remove stop words.

# Model Architecture
The model architecture used in this notebook is a feedforward neural network with three layers:

- An input layer with a size equal to the size of the vocabulary
- A layer for tokenizing the words
-An output layer with a single unit and a sigmoid activation function
The model is trained using binary cross-entropy loss and Adam optimizer.

# Results
The model achieves an accuracy of 78.6% on the test set after training for 5 epochs. The model is also evaluated using precision, recall, and F1 score.

# Conclusion
This notebook demonstrates how to build an NLP model using TensorFlow to predict if a tweet is about a real disaster or not. The model achieves good accuracy on the test set and can be used for further analysis of the Disaster Tweets dataset or similar datasets.



