# Alzheimer's Detection Using EEG Data

This repository contains a project focused on detecting Alzheimer's disease using EEG (Electroencephalogram) data. The aim is to leverage machine learning and signal processing techniques to classify EEG signals and evaluate the performance of different algorithms.

## Features

- **EEG Data Analysis**: Raw EEG data is processed to extract meaningful patterns.
- **Machine Learning Models**: Implementation of Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) for classification.
- **Statistical Feature Extraction**: Features like mean, standard deviation, and more are calculated from EEG signals to improve classification accuracy.
- **Wavelet Transform Analysis**: Application of wavelet transform for time-frequency domain analysis.
- **Autoencoder Usage**: Exploration of autoencoders for dimensionality reduction and improved classification.

## Project Workflow

1. **Phase 1**: Apply machine learning models on raw EEG data and calculate their performance metrics.
2. **Phase 2**: Extract statistical features from the EEG data and re-evaluate models.
3. **Phase 3**: Integrate autoencoders to preprocess data and optimize model performance.

## Data

- EEG data includes two main categories:
  - `Healthy`: Signals from healthy individuals.
  - `AD`: Signals from individuals diagnosed with Alzheimer's disease.
- Data is organized into subfolders for "eyes closed" and "eyes open" conditions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ramisk2000/Analysis-of-EEG-for-the-Detection-of-Alzheimer-s-Disease.git
   cd Analysis-of-EEG-for-the-Detection-of-Alzheimer-s-Disease
2. Install the required dependencies:
      pip install -r requirements.txt
Ensure your environment supports Jupyter Notebooks if you wish to run the .ipynb files.

3.Usage
Data Preprocessing: Scripts for cleaning and preparing EEG data.
Model Training: Code for training machine learning models on processed data.
Evaluation: Tools for assessing model performance using metrics like accuracy, precision, and recall.
4.Results
Performance metrics for each phase will be documented, highlighting the most effective model and feature set for Alzheimer's detection.

5.Future Improvements
Explore deep learning approaches for better accuracy.
Extend the dataset to include more diverse signals.
Implement real-time EEG signal analysis.
6.Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.


