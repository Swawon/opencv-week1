# OpenCV Fundamentals - Week 1

## 📌 Overview
This repository contains the code, notes, and research for **OpenCV Fundamentals - Week 1**.  
The goal of this assignment is to build a solid foundation in OpenCV, covering its core modules, image processing techniques, and practical applications.  
Both theoretical and practical components are included, with examples in Python using `cv2` and supporting libraries.

---

## 📖 Topics Covered
1. **Introduction to OpenCV** – history, installation, and setup.
2. **Core Functionality (`core` module)** – matrices, arrays, and utility functions.
3. **Image Processing (`imgproc` module)** – transformations, filtering, histograms.
4. **Application Utils (`highgui`, `imgcodecs`, `videoio`)** – display, I/O.
5. **Camera Calibration & 3D Reconstruction (`calib3d`)** – intrinsic/extrinsic parameters, stereo vision.
6. **Object Detection (`objdetect`)** – Haar cascades, face detection.
7. **2D Features Framework (`feature2d`)** – SIFT, ORB, feature matching.
8. **Deep Neural Networks (`dnn`)** – loading and running pre-trained models.
9. **Graph API (`gapi`)** – pipeline-based execution.
10. **Other Modules** – `ml`, `photo`, `stitching`, `video`.
11. **Theory of Image Processing** – pixels, convolution, edge detection, Fourier transforms.

---

## 📜 Exercises Included
- Loading and displaying images.
- Reading and writing video streams.
- Image transformations (resize, rotate, crop).
- Applying Gaussian blur and edge detection.
- Drawing shapes and adding text.
- Capturing and processing webcam feed in real-time.
- Saving processed videos.
- Feature detection and matching.
- Face detection with Haar cascades.
- Simple DNN-based object detection.

---



## ⚙ Installation & Usage

```bash
git clone https://github.com/Swawon/opencv-week1.git
cd opencv-week1
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
jupyter opencv_exercise_notebook.ipynb
