# GPU-Accelerated Pothole Detection using CUDA

## Overview

This project implements a **CUDA-based image processing pipeline** for pothole detection using GPU acceleration. It applies grayscale conversion, Gaussian blur, Sobel edge detection, and thresholding to identify road surface damage.

---

## Features

* Parallel image processing using CUDA
* Gaussian filtering for noise reduction
* Sobel edge detection
* Binary thresholding
* Texture memory optimization for faster access

---

## Pipeline

1. Grayscale conversion
2. Gaussian blur
3. Sobel edge detection
4. Thresholding

Each pixel is processed in parallel on the GPU for improved performance.

---

## Performance

* Faster than CPU implementation
* Optimized using texture memory for better spatial locality 

---

## Limitations

* Fixed thresholding
* Works on static images only
* Requires raw RGB input



