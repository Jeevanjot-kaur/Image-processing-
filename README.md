# Image-processing-

## Overview

This Python script performs edge detection on an input image using the Sobel operator and additional techniques. It enhances the contrast, applies Gaussian blur, calculates gradients, performs non-maximum suppression, and applies double thresholding for edge detection.

## Steps
Code is implemented using the Canny edge detection algorithm:
Step-1: Noise reduction;
Step-2: Gradient calculation;
Step-3: Non-maximum suppression;
Step-4: Double threshold;
Step-5: Edge Tracking by Hysteresis.

Then Performed data pre-processing to normalize the images in terms of Resolution, Image Size in pixel, and image compression. Then Created 3 sets of image datasets by creating variation of any image parameters.

## Install Dependencies:

Ensure you have the required dependencies installed:
pip install opencv-python matplotlib numpy

## View the Results:
The script will display intermediate and final results of the image processing steps, including gradient calculations, non-maximum suppression, and the resulting edges.

## Dependencies
OpenCV (cv2): Library for computer vision tasks.
NumPy: Library for numerical operations.
Matplotlib: Library for creating visualizations.
