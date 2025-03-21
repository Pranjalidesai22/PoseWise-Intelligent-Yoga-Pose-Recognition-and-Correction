# PoseWise-Intelligent-Yoga-Pose-Recognition-and-Correction

# Yoga Pose Recognition from Videos

## Project Overview

This project focuses on recognizing yoga poses from video data using deep learning techniques. The aim is to provide accurate pose predictions and offer real-time feedback for pose correction, enhancing the overall yoga experience. By leveraging computer vision and machine learning, the system detects poses, calculates angles, and offers actionable insights.

## Problem Statement

Yoga has gained immense popularity due to its numerous physical and mental benefits. However, incorrect posture and misalignment can lead to injuries. This project uses computer vision and deep learning to provide real-time pose recognition and feedback to ensure proper alignment and reduce injury risks.


## Research Questions

- How can we accurately recognize yoga poses from videos?
- What key data points and features are essential for accurate pose prediction?
- How can we effectively capture temporal features using sequential data?


## Data Overview

- **Dataset**: Yoga pose images and videos from multiple sources, including Kaggle and Sketchfab 3D models.
- **Training Data**: 5000 images
- **Testing Data**: 1600 images
- **Classes**:  
  - Warrior II  
  - Plank  
  - Downward Dog  
  - Tree  

## Methodology

1. **Data Collection and Preprocessing**  
    - Data was collected from open-access datasets and standardized.
    - Keypoints were extracted using **Mediapipe** to detect body landmarks.

2. **Feature Engineering**  
    - Joint angles were calculated using vector representations and trigonometry.
    - Extracted angles were used as primary features for model training.

3. **Model Development**  
    - Built deep learning models using frameworks like **TensorFlow** and **Keras**.
    - Models include Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTMs) networks for sequential data analysis.

4. **Pose Correction and Feedback**  
    - Deviations from reference angles were calculated.
    - Real-time feedback was generated to assist users in adjusting their poses.

## Results

- **Accuracy**: Achieved over **85%** accuracy in pose recognition within controlled environments.
- **Real-Time Feedback**: Provided actionable feedback using predefined angle thresholds.
- **Webcam Integration**: Demonstrated successful pose recognition using webcam input.
