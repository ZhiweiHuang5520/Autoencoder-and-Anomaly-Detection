# Autoencoder-and-Anomaly-Detection
This is HW 2 of ECE 228 at UCSD. 
2.1 Vanilla Autoencoder
Autoencoders are a simple but useful model. Similar to how a one-hot encoding transforms data into a
useful form for a particular network. Autoencoders provide powerful nonlinear encoding of data by squeezing the
data through a “bottleneck” called the latent space. Which in a sense filters the data down to a sparse basis or
representation of the data. The goal is to find a smallest latent space which gives a highly accurate reconstruction of
the data.  
2.2 Convolutional Autoencoder
A more powerful and complex form of autoencoder which can combine local information to create
complex abstract features across 2D image patches. Using max pooling provides invariant features while only
using convolution layers to reduce feature map size yields equivariant features. Deliverables: A working model
according to the design specified and latent space representation.  

2.3 Anomaly Detection
In this section, having a dataset of vibration data coming from a machine pump. The data has 8
channels, one for each acoustic sensor location. There is background noise. Your goal is to construct an autoencoder
that can detect the anomaly data. You are free to approach this as you see fit with the only stipulation being that you
can outperform a baseline model by finding more than 75 of the 143 anomalies. The data was created using the
torchaudio MelSpectrogram function and is a subset of a newer dataset developed for machine condition detection.
This data can be used for class projects and the melspectrogram starter code can be used for anyone working with
acoustic data.
