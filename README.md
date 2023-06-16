# HelloBud! - Machine Learning Model
> This is a repository for building the Machine Learning model for the HelloBud! application, a vocabulary learning app for in early childhood education. 


## Table of contents
* [Description](#description)
* [Datasets](#datasets)
* [Link to papers related](#link-to-papers-related)


## Description
This machine learning model is built to predict the voice of the user. The model's task is to detect and also classify the voice of the user. We convert audio waveform data into spectrograms. The model is built based on tensorflow and keras using simple convolutional neural network (CNN) to obtain features from the spectrogram image. There are 15 classes, including 'ayam', 'nanas', 'sapi', 'kucing', 'telinga', 'mata', 'pisang', 'semut', 'mangga', 'lidah', 'kambing', 'jeruk', 'kulit', 'apel', and 'hidung'.

## Datasets
The dataset used is the dataset created by our team. These are the following links:
https://drive.google.com/file/d/11Krasc-EOa3VKkLZd9JGQpLMu8M8uFQV/view?usp=drive_link

## Link to papers related
- Short-time Fourier Transform (STFT) : https://www.proquest.com/openview/605020c9c28280ce5db721b2d242c0fe/1?pq-origsite=gscholar&cbl=5444811

## How to use
Open to notebooks (.ipynb) files in colab, there will be instruction in how to run the training in the notebooks.
