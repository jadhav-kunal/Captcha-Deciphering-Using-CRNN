# Captcha-Deciphering-Using-CNN+RNN

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

In this application, variations of complex text-based CAPTCHA images will be provided with number of letters, dimensions of images and distortions.

A framework is proposed to decipher the complex text-based CAPTCHAs. 

The proposed framework is based principally on conventional steps of decoding CAPTCHAs (i.e. preprocessing, segmentation and recognition). 

This project demonstrates a simple OCR model built with the Functional API. Apart from combining CNN and RNN, it also illustrates how you can instantiate a new layer and use it as an "Endpoint layer" for implementing CTC loss.



### Convolutional Recurrent Neural Network

The CRNN approach identifies words using three steps:

1.A standard convolutional neural network (CNN) — the first layer breaks the image into features and is divided into “feature columns”.

2.These columns are fed into a deep-bidirectional long short term memory (LSTM) cell, which provides a sequence, identifying the relationship between the characters.

3.The output of the LSTM cell is fed into a transcription layer, which takes the character sequence, including redundant characters, and uses a probabilistic approach to clean the output.


### Dataset
The images are 5 letter words that can contain numbers.
The images have had noise applied to them (blur and a line). 
They are 200 x 50 PNGs.
Dataset contains 1070 files.

[![dataset](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/fournierp/captcha-version-2-images)
