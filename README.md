# 🛡️ Face Mask Detection System

A real-time deep learning-based system that detects whether a person is wearing a face mask using webcam video. It uses a Convolutional Neural Network (CNN) for classification and OpenCV for face detection and real-time webcam handling.

---

## 📌 Features

- Real-time face detection using webcam
- Binary classification: **With Mask** 😷 or **No Mask** ❌
- Alerts when a face without a mask is detected
- Lightweight and easy to run on most systems

---

## 🧰 Tools and Libraries Used

- Python 3.10
- TensorFlow / Keras
- OpenCV
- NumPy
- Haar Cascade (for face detection)

---

## 📁 Dataset

Dataset used: [Face Mask Dataset – Kaggle](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)

The dataset contains images in two categories:
- `with_mask`
- `without_mask`

---

## 🚀 How to Run

1. **Prepare Dataset**
    - Download the dataset from Kaggle and place it inside a folder named `dataset/`
    - Use the provided script to split into training and validation sets

2. **Train the Model**
    - Run the training script to create `mask_detector_model.h5`

3. **Run Real-Time Detection**
    - Start the detection script to activate the webcam and monitor mask status

---

## 🏗️ Project Structure

├── dataset/ 
├── data/ 
│ ├── train/
│ └── val/
├── mask_detector.py 
├── train_model.py 
├── split_data.py 
├── mask_detector_model.h5 
├── readme.md 
