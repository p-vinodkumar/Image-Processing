# Image Processing and Augmentation Toolkit

This repository contains various Python scripts for image processing, enhancement, augmentation, and noise removal. The toolkit utilizes libraries like OpenCV, TensorFlow, PIL, and Matplotlib to provide functionality for different types of image manipulations.

## Content:
- Image Thresholding
- Histogram Plotting
- Contrast Enhancement
- Image Filtering and Noise Removal
- Image Augmentation
- Image Scaling and Resizing

## Features:

### 1. Image Thresholding
- **Manual Thresholding**: Convert an image into a binary format based on a custom intensity threshold.
- **Binary Thresholding**: Split image pixels into foreground and background using different thresholds.

### 2. Histogram Plotting
- Plot the histograms of RGB and grayscale images to visualize pixel intensity distributions.

### 3. Contrast Enhancement
- **Histogram Equalization**: Improve the contrast by equalizing the histogram.
- **CLAHE (Contrast Limited Adaptive Histogram Equalization)**: Perform adaptive histogram equalization to enhance local contrast.
- **Manual Contrast Adjustment**: Use linear scaling (adjust alpha and beta) to manually modify the contrast and brightness of an image.

### 4. Image Filtering and Noise Removal
- **Gaussian Blur**: Smooth the image by averaging pixel values with a Gaussian kernel.
- **Median Blur**: Reduce noise by replacing each pixel with the median of neighboring pixels.
- **Bilateral Filter**: Smooth the image while preserving edges.
- **Noise Removal**: Apply a median filter to remove salt-and-pepper noise from an image.

### 5. Image Augmentation
Apply a series of augmentations (rotation, scaling, flipping, etc.) to increase the diversity of training data for machine learning models. The augmentation process includes:
- **Rotation**: Randomly rotate the image by a certain range.
- **Shift**: Apply random width and height shifts.
- **Shear**: Apply random shearing transformations.
- **Zoom**: Apply random zoom transformations.
- **Flip**: Flip images horizontally.

### 6. Image Scaling and Resizing
- Resize images to a specified dimension and scale pixel values to the range [0, 1].

### 7. Noise Addition
- **Salt-and-Pepper Noise**: Introduce random salt-and-pepper noise to simulate real-world imperfections in images.

### 8. Requirements:
-Python 3.x

-OpenCV

-TensorFlow

-PIL (Pillow)

-Matplotlib

-Numpy

### Installation

To install the required dependencies for the project, run the following command:

```bash
pip install -r requirements.txt
