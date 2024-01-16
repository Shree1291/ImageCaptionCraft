# ImageCaptionCraft

## Overview
This repository contains the implementation of an Image Caption Generator, leveraging a combination of Convolutional Neural Networks (CNNs) for image feature extraction and Long Short-Term Memory (LSTM) networks for generating descriptive captions.

## Features
- **Data Loading and Preprocessing:** Utilizes the Flickr8k dataset, encompassing image data and corresponding captions.
- **Feature Extraction:** Employs a pre-trained VGG16 model to extract features from images.
- **Caption Preprocessing:** Cleans and preprocesses captions for effective training.
- **Tokenization:** Implements a tokenizer to handle text data and create a vocabulary.
- **Model Architecture:** Structured combination of image and textual features for caption generation.
- **Training:** Model training through a data generator for efficient processing of large datasets.
- **Evaluation:** Utilizes BLEU scores for evaluating the quality of generated captions.
- **Caption Generation:** Functionality to generate captions for new images using the trained model.

## Usage
1. **Data Setup:** Ensure the Flickr8k dataset is available and properly formatted.
2. **Model Training:** Execute the provided Jupyter notebook to train the image caption generator model.
3. **Evaluation:** Evaluate the model's performance using BLEU scores on a test set.
4. **Caption Generation:** Use the trained model to generate captions for new images.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- NumPy
- NLTK

## References
- VGG16: [Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." arXiv preprint arXiv:1409.1556 (2014).](https://arxiv.org/abs/1409.1556)

## Acknowledgments
This project is part of a design project for [Your Course/Institution]. Feel free to explore, contribute, and adapt the code for your own image captioning projects!
