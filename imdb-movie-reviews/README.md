# IMDB Dataset of 50K Movie Reviews

In this notebook, we perform a sentiment analysis on a Kaggle dataset of movie reviews. Here is the description from Kaggle:

> *IMDB dataset having 50K movie reviews for natural language processing or Text analytics. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training and 25,000 for testing. So, predict the number of positive and negative reviews using either classification or deep learning algorithms.*

Our approach features a recurrent neural network with a long short-term memory (LSTM) cell. Step-by-step:

* Obtain the data from Kaggle.

* Split the data into train and test set as indicated (25K each).

* Preprocess the data by tokenizing words and forming a vocabulary.

* Form the LSTM neural network model.  

* Train the model using stochastic gradient descent.

* Evaluate the model on the test set.