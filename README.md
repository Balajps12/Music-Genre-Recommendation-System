# Music Genre Classification Recommendation System

## Description

This project classifies music genres using machine learning and deep learning techniques. It leverages the GTZAN dataset, a collection of 1000 audio files across 10 genres, for training and evaluation. The project implements various models such as Convolutional Neural Networks (CNN), Deep Neural Networks (DNN), and XGBoost to categorize music files into genres such as Blues, Hip-hop, Classical, and more. The goal is to offer personalized playlist recommendations based on the user's music preferences.

The system demonstrates the effectiveness of machine learning in music analysis and classification. With an accuracy rate of 92.93% on the test set, the CNN model emerges as the most efficient approach for music genre classification.

## Features

- **Music Genre Classification**: Classifies audio files into 10 genres.
- **Model Comparison**: Evaluates different machine learning algorithms including CNN, DNN, XGBoost, Random Forest, and Support Vector Machine (SVM).
- **High Accuracy**: Achieves a classification accuracy of 92.93% using CNN.
- **Feature Extraction**: Uses Discrete Fourier Transforms (DFT) and other techniques to extract key acoustic features from the audio files.
- **Performance Evaluation**: Utilizes metrics such as accuracy, precision, recall, and F1-score to assess model performance.

## Dataset

The GTZAN Genre Collection dataset is used for this project, which contains:

- 1000 30-second audio clips in `.wav` format.
- 10 genres: Blues, Hip-hop, Classical, Pop, Disco, Country, Metal, Jazz, Reggae, and Rock.
- Each genre has 100 files.

The dataset is publicly available on platforms like Kaggle.

## Results

| Model                               | F1-Score | Accuracy |
|-------------------------------------|----------|----------|
| XGBoost                             | 0.740    | 0.745    |
| Stochastic Gradient Descent         | 0.636    | 0.660    |
| MLP Classifier                      | 0.857    | 0.858    |
| Support Vector Machine              | 0.758    | 0.762    |
| Random Forest                       | 0.811    | 0.814    |
| Light Gradient Boosting Machine (LGBM) | 0.903 | 0.903    |
| Deep Neural Network (DNN)           | 0.923    | 0.933    |

## Future Scope

- **Fine-grained Genre Classification**: Classifying sub-genres and styles of music.
- **Multi-modal Approaches**: Integrating other features like lyrics or metadata for improved accuracy.
- **Real-time Classification**: Implementing real-time genre classification for music streaming applications.
- **Ethical Considerations**: Addressing privacy and data biases in music recommendation systems.
