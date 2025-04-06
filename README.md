# Speech_Emotion_Recognition
This project is a Speech and Video-Based Emotion Detection System built using Python, deep learning (CNN, LSTM), and Tkinter for GUI interaction. The system can detect emotions from both audio speech files and video face frames.


**🔍 Project Overview**

The system is divided into two main components:

+Speech Emotion Recognition (SER): Detects emotion from voice using Convolutional and LSTM-based neural networks.

+Facial Emotion Recognition (FER): Detects emotion from video frames/images using CNN and LSTM models

It is implemented in Python and offers a user-friendly GUI built with Tkinter for loading datasets, training models, and making predictions on both image and audio inputs.


**🧠 Features**

+Detect emotions from facial expressions using image datasets.

+Detect emotions from speech using audio datasets.

+Train using CNN and LSTM for both image and speech inputs.

+Real-time video-based emotion prediction.

+Metrics: Accuracy, Precision, Recall, F1-Score.



**🛠️ Tech Stack**

+Python

+Keras / TensorFlow

+OpenCV

+Librosa

+NLTK

+scikit-learn

+Tkinter GUI

+Matplotlib

+MoviePy, SpeechRecognition, SoundFile


**📊 Dataset**

Use datasets like:

+FER2013 or custom-labeled images for facial emotion detection.

+TESS, RAVDESS, or similar datasets for speech emotion recognition.

Place them inside the dataset/ folder, structured by emotion labels.

**👩‍💻 Developed With**

This system was developed as a research and learning project in the domain of Artificial Intelligence and Machine Learning. It demonstrates how multiple input modalities can be combined for emotion detection using deep learning.

**🚀 How It Works**

+Load Datasets: Load both facial emotion images and audio emotion recordings.

+Preprocessing: Resize images and extract MFCC, Chroma, and Mel features from audio.

+Model Training: Choose from CNN or LSTM models for both speech and image data.

+Evaluation: View model performance metrics.

+Prediction

  1.Upload an audio file to predict speech emotion.

  2.Upload a video to see real-time emotion recognition from facial expressions.

