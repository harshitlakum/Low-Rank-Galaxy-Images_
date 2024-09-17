# Low-Rank-Galaxy-Images

This repository contains a data science project focusing on the analysis of spiral galaxy images from the DESI Legacy Imaging Surveys. The project explores low-rank approximations to reduce the dimensionality and computational complexity of image processing, employing techniques such as SVD (Singular Value Decomposition) and wavelet transforms.

Project Overview
The goal of this project is to apply various image compression and feature extraction techniques to a dataset of 256 spiral galaxy images. These images are processed to understand the underlying structure and distribution of features across different bands (g, r, and z).
Repository Structure
•	Lab_Worksheet_3.ipynb: Main Jupyter notebook containing the analyses, including:
◦	RGB and grayscale image generation
◦	Down-sampling of images
◦	Low-rank wavelet and SVD approximations
◦	Comparison of different compression methods
◦	Exploration of singular vectors and convolutional autoencoder models

Techniques Used
•	Image Processing: Techniques to handle and transform images of galaxies into different formats for further analysis.
•	SVD and Wavelet Decomposition: Used to reduce the dimensionality of the images while preserving as much information as possible.
•	Machine Learning: Specifically, convolutional autoencoders to learn efficient representations of galaxy images.

