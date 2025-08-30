# Geometric-Transformations in Image Processing
This project demonstrates geometric transformations on images using OpenCV. It applies Euclidean, Similarity, Affine, and Projective transformations to show how rotation, scaling, translation, and perspective changes affect images. The notebook provides clear visual comparisons to make the concepts easier to understand.  
 
The goal of this project is to demonstrate how different geometric operations affect images and how these techniques are useful in **computer vision applications** such as object detection, perspective correction, image registration, and augmented reality.  

---

## Introduction

Geometric transformations are operations that modify the spatial relationship of pixels in an image.  
They are fundamental in image processing and computer vision because they help in aligning, scaling, rotating, and mapping images to new perspectives.  

This project covers four types of transformations:

1. **Euclidean Transformation**  
   - Preserves distances and angles  
   - Involves only **rotation** and **translation**  
   - Example: Moving or rotating an object without resizing it  

2. **Similarity Transformation**  
   - Preserves shape but allows **scaling**, **rotation**, and **translation**  
   - Example: Resizing an image while keeping proportions  

3. **Affine Transformation**  
   - Maps parallel lines to parallel lines  
   - Allows rotation, translation, scaling, and shearing  
   - Example: Skewing an image or applying perspective shifts  

4. **Projective Transformation (Homography)**  
   - The most general transformation  
   - Allows perspective distortion  
   - Example: Correcting perspective in scanned documents or aligning different views of an object  

---

## Technologies Used

- **Python 3.x**
- [OpenCV](https://opencv.org/) – for image processing and transformations  
- [NumPy](https://numpy.org/) – for numerical operations  
- [Matplotlib](https://matplotlib.org/) – for visualization  
- [Jupyter Notebook](https://jupyter.org/) – for interactive coding and demonstration  

