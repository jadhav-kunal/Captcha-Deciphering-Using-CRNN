# Captcha-Deciphering-Using-CNN+RNN

In this application, variations of complex text-based CAPTCHA images will be provided with number of letters, dimensions of images and distortions.

A framework is proposed to decipher the complex text-based CAPTCHAs. 

The proposed framework is based principally on conventional steps of decoding CAPTCHAs (i.e. preprocessing, segmentation and recognition). 

This project demonstrates a simple OCR model built with the Functional API. Apart from combining CNN and RNN, it also illustrates how you can instantiate a new layer and use it as an "Endpoint layer" for implementing CTC loss.



### Convolutional Recurrent Neural Network

The CRNN approach identifies words using three steps:

1.A standard convolutional neural network (CNN) — the first layer breaks the image into features and is divided into “feature columns”.

2.These columns are fed into a deep-bidirectional long short term memory (LSTM) cell, which provides a sequence, identifying the relationship between the characters.

3.The output of the LSTM cell is fed into a transcription layer, which takes the character sequence, including redundant characters, and uses a probabilistic approach to clean the output.


