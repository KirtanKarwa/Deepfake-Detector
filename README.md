# Deepfake-Detector

This is a Deepfake Detector project which detects if the input video is fake or real.  
The model is trained on a dataset containing fake and real videos. It uses a CNN architecture and facial landmark detection to classify whether the faces in the videos are fake (deepfakes) or authentic.

---

## 🧠 Deepfake Detector

### 🔍 Overview
This project is a Deepfake Detection system designed to identify manipulated facial videos using computer vision and deep learning techniques. It aims to combat the misuse of deepfake technology by detecting facial inconsistencies in video frames and flagging potential forgeries.

### 🎯 Objective
To develop a system that:
- Processes video files to extract individual frames
- Analyzes facial features to detect deepfakes
- Classifies videos as real or fake based on frame-level predictions

### 🛠️ Technologies Used
- **Python** – Core programming language
- **OpenCV** – Video frame extraction and image processing
- **Keras & TensorFlow** – Deep learning framework for model training
- **NumPy** – Numerical computations
- **Matplotlib** – Plotting training performance
- **MediaPipe** – Facial landmarks and mesh detection

### 📁 Project Structure
- `model.py` – Defines the deep learning architecture
- `train.py` – Handles model training using labeled video data
- `predict.py` – Performs inference on video files
- `utils/` – Utility functions (frame extraction, preprocessing, etc.)

### 📈 Model Details
- Architecture: Convolutional Neural Network (CNN)
- Input: Extracted face images from video frames
- Output: Binary classification – Real or Deepfake
- Dataset: Assumes usage of labeled video data (e.g., DFDC or FaceForensics++)

### 🧪 Features
- Frame-wise facial region detection using MediaPipe
- Video-to-frame extraction for preprocessing
- Confidence scores for each prediction
- Model performance visualization with accuracy and loss plots

### 🚀 Future Scope
- Real-time detection using webcam
- Heatmap overlays on tampered facial regions
- Integration with video surveillance or social plat
