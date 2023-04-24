# RNN text classification model for IMDB reviews

I love watching movies. It's a way to leave the world you live in and enter another, and for the length of a good movie you are completely captured by the emotions and themes within bringing new perspectives and thoughts. I also love discussing and reviewing movies, so after learning about the IMDB movie reviews dataset avaiable on tensorflow_datasets, I decided to join my hobby with my career skills and create this personal project on a model that can identify whether a review is positive or negative.

The format of the RNN model is built as a tf.keras.Sequential, with an encoder -> embedding -> RNNs -> final processing layers as the format (based off tutorials from tensorflow.org)
