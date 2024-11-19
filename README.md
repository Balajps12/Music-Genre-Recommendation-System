# MusicSense: A Machine Learning-Powered Music Recommendation System

## Overview

**MusicSense** is a machine learning-based project that classifies music genres and provides personalized playlist recommendations. Using the GTZAN dataset, which contains 1000 audio files from 10 different genres, the system employs machine learning and deep learning techniques to categorize music into genres such as Blues, Hip-hop, Classical, and more. The project explores various algorithms including Convolutional Neural Networks (CNN), Deep Neural Networks (DNN), and XGBoost to offer accurate music classification and personalized recommendations based on user preferences.

With an impressive accuracy rate of **92.93%** on the test set, the CNN model proves to be the most effective model for music genre classification in this project.

## Features

- **Music Genre Classification**: Classify audio files into 10 different music genres.
- **Model Comparison**: Evaluate the performance of various machine learning models, such as CNN, DNN, XGBoost, Random Forest, and Support Vector Machine (SVM).
- **High Accuracy**: Achieve a classification accuracy of **92.93%** using CNN for genre prediction.
- **Feature Extraction**: Extract meaningful acoustic features from audio files using Discrete Fourier Transform (DFT) and other signal processing techniques.
- **Performance Metrics**: Use accuracy, precision, recall, F1-score, and other evaluation metrics to assess model performance.

## Dataset

The **GTZAN Genre Collection** dataset is used for this project. This dataset contains:

- **1000 audio clips** of 30 seconds in `.wav` format.
- **10 distinct genres**: Blues, Hip-hop, Classical, Pop, Disco, Country, Metal, Jazz, Reggae, and Rock.
- **100 audio files per genre**.

The GTZAN dataset is publicly available on platforms like Kaggle and serves as a benchmark for genre classification tasks.

## Results

Below are the evaluation results for different models, showcasing their **F1-Score** and **Accuracy** on the test dataset:

| Model                                    | F1-Score | Accuracy |
|------------------------------------------|----------|----------|
| **XGBoost**                              | 0.740    | 0.745    |
| **Stochastic Gradient Descent (SGD)**    | 0.636    | 0.660    |
| **MLP Classifier**                       | 0.857    | 0.858    |
| **Support Vector Machine (SVM)**         | 0.758    | 0.762    |
| **Random Forest**                        | 0.811    | 0.814    |
| **Light Gradient Boosting Machine (LGBM)** | 0.903  | 0.903    |
| **Deep Neural Network (DNN)**            | 0.923    | 0.933    |

## Future Scope

**MusicSense** has significant potential for future development:

- **Fine-grained Genre Classification**: Expanding the model to classify sub-genres and styles within each genre.
- **Multi-modal Approaches**: Combining audio features with metadata, lyrics, and other attributes to improve classification performance.
- **Real-time Classification**: Implementing real-time music genre classification for music streaming platforms or mobile applications.
- **Ethical Considerations**: Addressing concerns related to privacy and biases in music recommendation systems, ensuring fair and transparent algorithms.

## Getting Started

### Prerequisites

To run this project locally, ensure you have the following dependencies installed:

- Python 3.x
- Required Python libraries (listed in `requirements.txt`)


