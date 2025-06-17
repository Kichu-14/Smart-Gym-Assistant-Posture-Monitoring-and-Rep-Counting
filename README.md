# Smart-Gym-Assistant-Posture-Monitoring-and-Rep-Counting
A real-time fitness assistant that detects push-up posture and counts reps using computer vision and deep learning. Built with Python, OpenCV, MediaPipe, and a custom CNN model for accurate form correction and tracking.

## 📂 Project File Overview

| File Name              | Description                                                                                          |
|------------------------|------------------------------------------------------------------------------------------------------|
| `Dataset.ipynb`        | Extracts video frames, converts them to grayscale, resizes images, and labels them for CNN training. |
| `Train_Video.ipynb`    | Captures live push-up footage to generate and store labeled image samples for dataset creation.      |
| `Training_model.ipynb` | Defines and trains a CNN model using TensorFlow/Keras to classify correct and incorrect postures.    |
| `Prediction.ipynb`     | Applies MediaPipe for real-time pose tracking and uses the trained model to evaluate form and count reps. |

Authors: Arya Jayasankar,Krishnendu M Uday and Ishaan Shokeen
