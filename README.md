# Face Liveness Detection

This repository contains the implementation of a Face Liveness Detection system. The system is designed to distinguish between real and fake faces in images or video streams, a critical feature for preventing spoofing attacks in facial recognition systems.

---

## Features

- **LivenessNet Model**: A deep learning-based model to detect liveness.
- **Training and Evaluation**: Includes training and testing scripts for liveness detection.
- **Demo Application**: `demo.py` allows you to test the liveness detection system on sample inputs.
- **Docker Support**: Easily set up the environment using the provided `docker.yml` file.

---

## Requirements

- **Python** 3.8 or later
- Required libraries (install using `requirements.txt`):
  - OpenCV  
  - TensorFlow/Keras  
  - NumPy  
  - Matplotlib  

---

## Usage

### 1. Clone the Repository

```bash
git clone https://github.com/username/face-liveness-detection.git
cd face-liveness-detection
