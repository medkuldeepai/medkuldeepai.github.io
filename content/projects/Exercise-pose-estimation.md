---
title: "Exercise Pose Estimation using MediaPipe"
date: 2025-02-01
---

# Exercise Pose Estimation using MediaPipe

## Overview

Developed a real-time exercise posture analysis system using MediaPipe Pose to detect and evaluate squat movements from webcam video streams. The system estimates human body landmarks, calculates joint angles, and provides feedback on squat form to assist users in performing exercises correctly.

## Motivation

Incorrect squat posture can increase the risk of injury and reduce exercise effectiveness. This project explores the use of computer vision and pose estimation techniques to automatically monitor exercise form and provide real-time feedback without requiring wearable sensors.

## Methodology

### Pose Detection

- Utilized MediaPipe Pose to detect 33 human body landmarks in real time.
- Extracted key lower-body landmarks including:
  - Hip
  - Knee
  - Ankle

### Joint Angle Calculation

- Computed knee and hip joint angles using geometric relationships between detected landmarks.
- Tracked angle variations throughout the squat movement cycle.

### Squat Classification

The system classified squat states based on joint angle thresholds:

- Standing Position
- Descending Phase
- Bottom Squat Position
- Ascending Phase

### Real-Time Feedback

Provided visual feedback including:

- Body landmark visualization
- Joint angle measurements
- Squat repetition counting
- Posture quality assessment

## Results

- Achieved reliable real-time pose tracking using a standard webcam.
- Successfully detected squat repetitions and movement phases.
- Demonstrated the feasibility of vision-based exercise monitoring without specialized hardware.

## Technologies Used

- Python
- MediaPipe
- OpenCV
- NumPy

## Key Concepts

- Human Pose Estimation
- Computer Vision
- Biomechanics
- Real-Time Video Processing
- Joint Angle Analysis

## Future Improvements

- Support for multiple exercises (push-ups, lunges, planks).
- Deep learning-based posture quality scoring.
- Personalized exercise coaching.
- Mobile and web deployment.