# Project - ObjectSizeEstimator
# Introduction
The Object Size Estimator is a Python-based tool that uses computer vision and NumPy to estimate the size of objects in images. This project leverages the power of OpenCV for image processing and NumPy for numerical operations.
# Features
1. Detects objects in images.
2. Estimates the size of detected objects.

# Steps Involved 

# Pre-processing the Image.

Convert the image to grayscale.
Apply Gaussian blur to reduce noise.
Use edge detection (e.g., Canny) to find edges in the image.
Finding Contours:

# Identify all contours in the pre-processed image.
Select the biggest contour, which is assumed to be the object of interest.
Measuring Size:

# Calculate the bounding box or minimum enclosing rectangle for the biggest contour.
Measure dimensions such as width and height.
Optionally, apply a reference object for real-world size estimation.

# Examples
![Screenshot (8)](https://github.com/Jashwanth-Ram/ObjectSizeEstimator/assets/122851926/e51ddf54-8fa2-4338-bc79-07d8368512ea)

