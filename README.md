# Histogram Equalization with CUDA

This project implements a system for computing and visualizing the histogram equalization of an image, supporting both grayscale and color formats. It includes:

- ✅ A **sequential version** of the histogram equalization algorithm written in C++
- 🚀 A **parallel version** using **CUDA**, leveraging GPU acceleration for faster processing
- 📊 Generation of the original and equalized histograms
- 🖼️ Visualization of both the original and processed images

The project was developed and tested using **Google Colab** and supports user-provided input images.

## Features

- Global histogram equalization in C++ (CPU and GPU)
- CUDA-based parallel implementation for high performance
- Support for grayscale and RGB images
- Histogram plotting and image comparison

## Usage

To run the notebook:

1. Open `Cuda_colab.ipynb` in Google Colab
2. Upload an image of your choice
3. Run all cells to visualize the original and equalized histograms and images

## Requirements

- Google Colab with GPU enabled
- C++ and CUDA environment preconfigured in Colab
- Python (used only for plotting and visualization)

## Output

For each input image, the notebook will generate:

- Original image
- Equalized image
- Histogram before equalization
- Histogram after equalization



