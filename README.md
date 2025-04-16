

# Audio Classification

This project classifies audio data into two classes using machine learning.

## Dataset

The dataset contains audio files with labels "0" and "1." Features are extracted using **MFCCs**, **Spectral Features**, and **Zero Crossing Rate**. You can access the dataset [here](https://github.com/Jakobovski/free-spoken-digit-dataset).

## Libraries

- `pandas`, `numpy`, `librosa`, `scikit-learn`, `matplotlib`

## Features

- **MFCCs**, **Spectral Centroid**, **Zero Crossing Rate**, **Chroma**, and **Tonnetz**

## Models

- **Gaussian Naïve Bayes** and **Logistic Regression** models, with **Bagging** applied.

## Evaluation

Metrics: **Accuracy**, **Precision**, **Recall**, **F1-Score**

## Setup

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/audio-classification.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The features CSV is available [here](https://github.com/Jakobovski/free-spoken-digit-dataset).

