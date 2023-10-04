# Simple_Autoencoder

Autoencoders are a type of neural network that has become increasingly popular in recent years
due to their ability to learn efficient data representations without the need for labeled data. It
consists of Three parts: an encoder, botleneck and decoder. The encoder takes an input with high dimension and produces
a compressed representation of it(Botleneck), while the decoder takes this compressed representation and
produces a reconstruction of the original input. Autoencoders is an unsupervised learning model. 
The objective of autoencoders is to minimize the reconstruction error between the original input
data and its reconstructed output, while also minimizing the size of the compressed representation.
By doing so, autoencoders can learn a compressed representation of the input that can be used for
tasks such as dimensionality reduction, feature extraction, or anomaly detection.
This project use the Mnist dataset to train a simple autoencoder using different activation funtion as well as the different metric for evaluation.
