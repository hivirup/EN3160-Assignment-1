# EN3160 Assignment 1: Intensity Transformations and Neighborhood Filtering

## Overview
This repository contains the Jupyter Notebook implementation and exported report for EN3160 Assignment 1. The project explores fundamental computer vision and digital image processing concepts, focusing on manipulating image intensities, equalizing histograms, and applying spatial filters to extract or enhance features. 

## Key Implementations
The assignment consists of algorithm development and practical applications across several domains of image processing:

*   **Intensity Transformations:** Custom breakpoint piecewise linear transformations, gamma correction in the L*a*b* color space, and vibrance enhancement in the HSV color space.
*   **Histogram Processing:** Global histogram equalization and targeted foreground-only histogram equalization using binary masking.
*   **Neighborhood Filtering:** Edge detection and gradient computation using the Sobel operator (both built-in and custom implementations).
*   **Image Scaling:** Implementation of nearest-neighbor and bilinear interpolation for image zooming, evaluated using normalized Sum of Squared Differences (SSD).
*   **Image Segmentation & Enhancement:** Foreground extraction using the GrabCut algorithm and background blurring.
*   **Edge-Preserving Smoothing:** Implementing and comparing custom and built-in bilateral filters for noise reduction while maintaining sharp edges.

## Technologies Used
*   Python
*   Jupyter Notebook
*   OpenCV (cv2)
*   NumPy
