# 🚗 Automatic License Plate Recognition using OCR

## 📌 Overview

This project implements an **Automatic License Plate Recognition (ALPR)** system using **Computer Vision** and **Optical Character Recognition (OCR)** techniques.

The system detects a vehicle's license plate from an image, extracts the plate region, and recognizes the text using EasyOCR.

---

## 🎯 Objective

The main objective of this project is to automatically detect and recognize vehicle license plate numbers from images using image processing and OCR techniques.

---

## 📊 Project Workflow

1. Read the input vehicle image.
2. Convert the image to grayscale.
3. Apply bilateral filtering for noise reduction.
4. Detect edges using the Canny Edge Detector.
5. Find contours and identify the license plate.
6. Crop the detected license plate.
7. Extract text using EasyOCR.
8. Display the detected plate with the recognized text.

---

## 🖼️ Results

### Original Vehicle Images

![Car 1](car1.png)

![Car 2](car2.png)

---

### License Plate Detection

![Detection Result](detection_result.png)

---

### Final OCR Result

![OCR Result](ocr_result.png)

The system successfully detects the vehicle's license plate and recognizes the license number using EasyOCR.

---

## 🛠️ Technologies Used

* Python
* OpenCV
* EasyOCR
* NumPy
* Matplotlib
* Imutils

---

## 📦 Required Libraries

```bash
pip install opencv-python
pip install easyocr
pip install imutils
pip install matplotlib
pip install numpy
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the notebook.
4. Run all cells.
5. Replace the input image with your own vehicle image to test the model.

---

## 📁 Project Structure

```text
Automatic-License-Plate-Recognition/
│
├── OCR.ipynb
├── car1.png
├── car2.png
├── detection_result.png
├── ocr_result.png
├── README.md
└── requirements.txt
```

---

## 🚀 Features

* Vehicle license plate detection.
* Image preprocessing using OpenCV.
* Automatic text extraction using EasyOCR.
* Supports different vehicle images.
* Simple and efficient Computer Vision pipeline.

---

## 👩‍💻 Author

**Meriam Aziz**

---

## ⭐ Future Improvements

* Process video streams in real time.
* Improve detection accuracy under different lighting conditions.
* Support multiple license plates in a single image.
* Build a web application using Streamlit or Flask.

