This repository provides implementations of various image noise filtering techniques to improve image quality. Noise in images can degrade visual information and hinder image analysis tasks. By applying effective filtering techniques, we can reduce noise and enhance image clarity.

Techniques Implemented

Spatial Domain Filtering:
Averaging Filter: Reduces noise by averaging pixel values within a neighborhood.
Median Filter: Replaces each pixel with the median value of its neighbors, effectively removing salt-and-pepper noise.
Gaussian Filter: Applies a Gaussian kernel to smooth the image, reducing Gaussian noise.
Frequency Domain Filtering:
Fourier Transform: Transforms the image from spatial domain to frequency domain.
Ideal Low-Pass Filter: Removes high-frequency noise components.
Butterworth Low-Pass Filter: Gradually attenuates high frequencies.
Gaussian Low-Pass Filter: Smoothly attenuates high frequencies.
Usage

Install Required Libraries:
Bash

pip install opencv-python numpy matplotlib
Run the Script: Execute the Python script to apply the desired filter to an image.
Bash

python noise_filter.py
Customization

Filter Selection: Choose the appropriate filter based on the type of noise and desired level of smoothing.
Parameter Tuning: Adjust filter parameters (e.g., kernel size, cutoff frequency) to control the filtering process.
Image Input: Modify the script to accept different image formats and input paths.
Output Format: Customize the output image format and save location.
Future Work

Adaptive Filtering: Develop filters that adjust their parameters based on local image characteristics.
Non-Linear Filters: Explore non-linear filters (e.g., bilateral filter, wavelet filter) for more advanced noise reduction.
Deep Learning-Based Methods: Implement deep learning models for sophisticated noise removal.
