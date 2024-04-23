# Hand Gesture Data Collection using OpenCV and MediaPipe

This repository contains code for collecting hand images using OpenCV and MediaPipe. The collected data can be used for training machine learning models for various applications like gesture recognition, sign language translation, and more.

## Features
- Utilizes OpenCV for video capture and image processing.
- Integrates MediaPipe for hand detection and tracking.
- Easily adjustable parameters for image cropping and resizing.
- Saves collected images to specified folders for dataset creation.

## Usage
1. Ensure you have the required libraries installed. You can install them via pip:
```bash
pip install opencv-python mediapipe cvzone
```
2. Clone the repository:
```bash
git clone https://github.com/VivekSai07/Hand-Gesture-Data-Collection-using-OpenCV-and-MediaPipe.git
```
3. Run the Python script data_collection.py.
```bash
python dataCollection.py
```
4. Follow on-screen instructions to save hand images:
- Press 's' to save the current hand image.
- Press 'q' to quit the program.

## Dataset Structure
The collected images are saved in the Data directory. By default, left hand images are saved in the Data/Left folder. You can modify the script to save images for the right hand or adjust the folder structure as per your requirements.
