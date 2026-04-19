# 🖼️ Digital Image Processing: Edge Detection Tool

![Python](https://img.shields.io/badge/Language-Python-blue.svg)
![OpenCV](https://img.shields.io/badge/Library-OpenCV-green.svg)
![KFU](https://img.shields.io/badge/University-King%20Faisal%20University-green.svg)

## 📌 Project Overview
Edge detection is a fundamental tool in image processing and computer vision, particularly in the areas of feature detection and extraction. This project implements a pipeline to process raw images and extract clear boundaries using the **Canny Edge Detection** algorithm.

## 🛠️ Image Processing Pipeline
The tool follows a structured workflow to ensure high-quality edge extraction:
1. **Grayscale Conversion:** Converting the input image to grayscale to simplify the data by removing color information.
2. **Noise Reduction (Gaussian Blur):** Applying a 5x5 Gaussian filter to smooth the image and remove noise that could interfere with edge detection.
3. **Canny Edge Detection:** Applying the Canny algorithm with dual thresholds (100 and 200) to identify strong edges while suppressing weak ones.
4. **Visualization:** Comparing the original image vs. the edge-detected result using Matplotlib.

## 🚀 Key Results
Below is a sample of the edge detection result achieved by the tool:
<img width="796" height="503" alt="detection result" src="https://github.com/user-attachments/assets/7886f2ae-b37a-4e6f-920d-5faf96e509b5" />

## 🚀 Key Features
- **Noise Filtering:** Integrated Gaussian blur for better result accuracy.
- **Dynamic Processing:** Capable of processing various image formats through the OpenCV pipeline.
- **Side-by-Side Comparison:** Automated visualization of results for analytical review.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** OpenCV (`cv2`), Matplotlib (`plt`), NumPy.
- **Environment:** Jupyter Notebook.

## 📁 Repository Structure
- `Code/`: Contains the `File Project.ipynb` with the full implementation.
- `Images/`: Contains the original images and the processed results.

## 👥 The Team
Developed by Computer Science students at **King Faisal University**:
- **Atekah Hussain Aljafar**
- *Zainab Abdulkarim Alhadhari*
- *Anfal Ahmad Alsuhayib*
- *Maryam Ahmed Alshabib*

---
*Part of the Digital Image Processing Course (CS323) - KFU (2024-2025).*
---
*Connect with me on LinkedIn for more projects!*
[https://www.linkedin.com/in/ateka-hussain/](https://www.linkedin.com/in/ateka-hussain/)
