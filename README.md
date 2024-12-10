Project Overview
This project involves building a machine learning model for audio classification using Artificial Neural Networks (ANN). The audio data is preprocessed to extract Mel Spectrogram features, which effectively represent audio signals in a compact and informative format. The final model is capable of categorizing audio samples into predefined classes.

Features
Audio Preprocessing: Converts raw audio files into Mel Spectrograms.
Feature Extraction: Leverages time-frequency domain representation for efficient analysis.
Model Architecture: Implements a custom ANN optimized for classification tasks.
Scalable: Can be extended to multiple audio datasets and classes.

Folder Structure
audio-classification/
├── data/
│   ├── train/                # Training audio files
│   ├── test/                 # Testing audio files
├── features/
│   ├── mel_spectrograms/     # Extracted Mel Spectrograms
├── models/
│   ├── ann_model.h5          # Trained ANN model
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
├── scripts/
│   ├── preprocess_audio.py   # Audio preprocessing script
│   ├── train_model.py        # Model training script
├── README.md
