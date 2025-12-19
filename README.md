Emotion-Aware Movie Recommendation System 

> Problem Statement

Traditional movie recommendation systems rely on past ratings or user history and ignore the user’s current emotional state. This project aims to enhance personalization by recommending movies based on real-time facial emotion detection.

> Solution Overview

This system captures the user’s facial expression through a webcam, detects the emotion using a deep learning model, and recommends movies aligned with the detected emotion.

> Tech Stack

-Python

-OpenCV

-TensorFlow / Keras

-NumPy, Pandas

-Scikit-learn


> Workflow

1. Trained a Deep Learning CNN model on facial expression datasets to classify emotions (Happy, Sad, Angry, Neutral, Surprise, Fear)

2. Extracted movie features (genres, metadata) and applied K-Means clustering to group movies into emotion-aligned clusters

3. Linked each detected emotion to the most relevant movie cluster

4. Integrated the trained emotion model with OpenCV (cv2) to capture live webcam input and perform real-time emotion detection

5. Recommended movies from the selected cluster and displayed results to the user



> Model Details

CNN architecture trained on facial expression dataset

Emotions detected: Happy, Sad, Angry, Neutral, Surprise, Fear

Optimized using categorical cross-entropy and Adam optimizer


> Results

Accurate real-time emotion detection

Emotion-specific movie recommendations

End-to-end system demonstrating applied AI


> Future Improvements

Use transformer-based emotion recognition

Add collaborative filtering

Deploy as a web application
