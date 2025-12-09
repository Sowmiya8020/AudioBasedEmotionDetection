Audio-Based Emotion Detection:
A deep-learning–based system that identifies human emotions from speech audio using spectrogram analysis and neural networks.
This project supports applications in psychological analysis, emotion-aware AI systems, customer sentiment monitoring, and assistive technologies.

Project Structure:
audio-emotion-classification/
│
├── notebook.ipynb            # Training, preprocessing & prediction pipeline
├── Dataset_info.pdf          # Dataset description & details
├── requirements.txt          # Required Python libraries
└── images/                   # Sample spectrograms, output images

Features:
Audio Preprocessing
Converts raw audio into Mel Spectrograms
Normalization & noise reduction
Standardized sampling rate for all datasets

Deep Learning Models:
CNN / CNN-LSTM hybrid for spectrogram classification
Trained on multiple datasets for better generalization
Achieves high accuracy across different emotion categories

Datasets Used:
Your system uses diverse and well-known audio emotion datasets:
CREMA-D
TESS
RAVDESS
SAVEE
These datasets provide multi-speaker, multi-accent emotional speech for robust training.

Model Performance:
Achieved 81.23% accuracy
Generalizes across speakers, accents, and background variations
Handles multiple emotion categories (happy, sad, angry, neutral, etc.)

How It Works:
Load audio files
Generate Mel spectrograms
Feed spectrograms to the deep learning model
Predict emotion label
Visualize results using plots and confusion matrix

Tech Stack:
Python
TensorFlow / Keras
Librosa
NumPy
Matplotlib
Scikit-learn

Installation:
Step 1: Clone the repository
git clone https://github.com/Sowmiya8020/AudioBasedEmotionDetection.git
cd AudioBasedEmotionDetection
Step 2:Install dependencies
pip install -r requirements.txt

Results
Spectrogram visualizations
Training & validation accuracy curves
Confusion matrix
Emotion distribution plots
(All available in the images/ folder)

Dataset_info.pdf contains:
Dataset descriptions
Audio sample details
Emotion labels
Balanced dataset information
