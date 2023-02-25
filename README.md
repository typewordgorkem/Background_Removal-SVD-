#  Background_Removal-SVD-
This project was created to distinguish between the background of any video image and the objects on the video. As a method, "Naive" &amp; "Singular Value Decomposition" methods were processed and examined.


### Overview

Background removal is a common task in image processing, where the objective is to separate the foreground objects from the background of an image. Python is a popular programming language for image processing, and Jupyter Notebook is a widely used interactive development environment for Python. In this overview, we will discuss a background removal application written in Python and Jupyter Notebook that uses two methods: naive and singular value decomposition.

The naive method for background removal involves thresholding the image and setting all pixels with values below the threshold to zero. This method assumes that the background pixels have lower values than the foreground pixels, which is not always the case. However, the method is simple and fast, and it can work well if the image has a clear separation between the foreground and background.

The singular value decomposition (SVD) method for background removal is a more advanced technique that can work better than the naive method in many cases. SVD is a linear algebra technique that decomposes a matrix into three matrices: U, Σ, and V^T. The Σ matrix contains the singular values, which are sorted in decreasing order. The SVD method for background removal involves setting the smallest singular values to zero, reconstructing the matrix from the modified Σ matrix and the U and V^T matrices, and then thresholding the reconstructed matrix to obtain the foreground pixels.

The background removal application written in Python and Jupyter Notebook uses the OpenCV library to load and display the images, and it implements both the naive and SVD methods for background removal. The application allows the user to select an image, choose a method for background removal, and adjust the parameters of the method, such as the threshold value for the naive method and the number of singular values to keep for the SVD method. The application also displays the original and processed images side by side, allowing the user to compare the results.

In summary, the background removal application written in Python and Jupyter Notebook is a useful tool for separating the foreground objects from the background of an image. The application implements two methods: naive and SVD, which can work well in different scenarios. The application is easy to use and allows the user to adjust the parameters of the methods to obtain the desired results.

### Getting Started

#### Prerequisites

- OpenCV: OpenCV is a powerful computer vision library that provides various functions for image and video 
  processing. It is widely used for image segmentation, object detection, and tracking. OpenCV can be installed 
  using pip, and it is compatible with Python 3.

- NumPy: NumPy is a Python library that provides support for large, multi-dimensional arrays and matrices. It is widely used in scientific computing and image processing. NumPy can be installed using pip.

- Matplotlib: Matplotlib is a Python library that provides functions for creating static, animated, and interactive visualizations. It can be used to display and save images, histograms, scatter plots, and other types of plots. Matplotlib can be installed using pip.

- Jupyter Notebook: Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. It is widely used for interactive data analysis and scientific computing. Jupyter Notebook can be installed using pip or Anaconda.

### Installing
1. Clone the repository
```
git clone https://github.com/typewordgorkem/Background_Removal-SVD-
```
2. Just compile on Jupyter Notebook or supported IDE's.




