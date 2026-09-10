# EN3160 Assignment 1: Intensity Transformations and Neighborhood Filtering

## Overview
This repository contains the Jupyter Notebook implementation and exported report for EN3160 Assignment 1[cite: 1]. The project explores fundamental computer vision and digital image processing concepts, focusing on manipulating image intensities, equalizing histograms, and applying spatial filters to extract or enhance features[cite: 1]. 

## Key Implementations
The assignment consists of algorithm development and practical applications across several domains of image processing:

*   **Intensity Transformations:** Custom breakpoint piecewise linear transformations, gamma correction in the $L^{*}a^{*}b^{*}$ color space, and vibrance enhancement in the HSV color space[cite: 1].
*   **Histogram Processing:** Global histogram equalization and targeted foreground-only histogram equalization using binary masking[cite: 1].
*   **Neighborhood Filtering:** Edge detection and gradient computation using the Sobel operator (both built-in and custom implementations)[cite: 1].
*   **Image Scaling:** Implementation of nearest-neighbor and bilinear interpolation for image zooming, evaluated using normalized Sum of Squared Differences (SSD)[cite: 1].
*   **Image Segmentation & Enhancement:** Foreground extraction using the GrabCut algorithm and background blurring[cite: 1].
*   **Edge-Preserving Smoothing:** Implementing and comparing custom and built-in bilateral filters for noise reduction while maintaining sharp edges[cite: 1].

## Technologies Used
*   Python
*   Jupyter Notebook[cite: 1]
*   OpenCV (cv2)[cite: 1]
*   NumPy[cite: 1]
