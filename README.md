# Image-Compression
Auto Encoders for Image Compression 

## Auto Encoders
Autoencoder is a type of artificial neural network used for unsupervised learning. It is designed to learn a compressed representation of input data by encoding it into a smaller set of variables and then reconstructing it back from this compressed representation. Autoencoder is a powerful tool for dimensionality reduction, feature extraction, and anomaly detection.The architecture of an autoencoder consists of two main components: an encoder and a decoder. The encoder takes an input data vector and maps it into a lower-dimensional latent space representation. The decoder then takes the latent space representation and reconstructs the original input vector.

## Description: 
MNIST data set of 28 X 28 pixels is passed through artificial neural network to compress image to 8 X 4 pixels through encoder architecture and further, the compress image is reconstructed back to 28 X 28 pixels using decoder architecture. 

## Encoder Architecture
Input: 784 <br>
Hidden Layer: 3 <br>
Output: 32 <br>

<img src="https://github.com/bipulsimkhada/Image/blob/main/AE%20-%20encoder.png">

## Decoder Architecture
Input: 32 <br>
Hidden Layer: 3 <br>
Output: 784 <br>

<img src="https://github.com/bipulsimkhada/Image/blob/main/AE%20-%20dencoder.png">


## Input Image VS Compressed Image VS Constructed Image
<img src="https://github.com/bipulsimkhada/Image/blob/main/ae%20-%20result.png">
