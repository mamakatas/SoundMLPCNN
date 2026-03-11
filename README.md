# Audio Classification using MLP and CNN

This repository contains a Jupyter Notebook (`soundmlpcnn.ipynb`) dedicated to audio classification. It explores and compares the performance of two different neural network architectures: a Multi-Layer Perceptron (MLP) and a Convolutional Neural Network (CNN).

## Overview

The project demonstrates an end-to-end pipeline for processing audio signals and classifying them into discrete categories. It covers:
1. **Audio Preprocessing:** Loading raw audio files and converting them into a format suitable for machine learning.
2. **Feature Extraction:** Extracting key audio features (such as MFCCs or Mel-Spectrograms) to feed into the models.
3. **Multi-Layer Perceptron (MLP):** Building, training, and evaluating a baseline dense neural network.
4. **Convolutional Neural Network (CNN):** Building, training, and evaluating a CNN, which is typically well-suited for 2D representations of audio data.
5. **Model Comparison:** Analyzing the accuracy, loss, and overall effectiveness of both approaches.

## Datasets

Please note that the datasets used in this project are **not included** in this repository. To run the notebook successfully, you will need to provide your own audio dataset. 

* Create a dataset folder in the root directory (or update the path variables in the notebook).
* Organize your audio files (`.wav`, `.mp3`, etc.) into subdirectories based on their class labels before running the feature extraction cells.

## Requirements

To run the notebook, you will need Python 3.x and the following typical libraries (adjust based on the specific frameworks you used):

```bash
pip install numpy pandas matplotlib librosa scikit-learn tensorflow
