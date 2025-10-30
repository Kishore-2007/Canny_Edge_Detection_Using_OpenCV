# Canny_Edge_Detection_Using_OpenCV

## Aim:
To implement the Canny Edge Detection algorithm in Python using OpenCV, and visualize each step of the process — from grayscale conversion to Gaussian blur and final edge detection — on a sample image.

## Overview:
This project demonstrates how to apply Canny Edge Detection, a multi-stage algorithm used to detect edges in an image while minimizing noise.
It involves:

  -Converting the image to grayscale
  
  -Applying Gaussian Blur to remove noise
  
  -Detecting edges using Canny algorithm with two threshold values
  
  -Displaying all intermediate stages using Matplotlib

## Steps Performed:
  1.Read the input image using OpenCV.
  
  2.Resize the image for uniform processing.
  
  3.Convert the image to grayscale.
  
  4.Apply Gaussian Blur to reduce noise and smooth the image.
  
  5.Perform Canny Edge Detection using two threshold values.
  
  6.Display all stages — original, grayscale, blurred, and edge-detected — using Matplotlib.

## Tech Used:
  ~ Python 3.x
  
  ~ OpenCV (cv2)
  
  ~ Matplotlib

## Result:
The Canny algorithm successfully detects clear, continuous edges while suppressing noise.Gaussian Blur improves the quality of detected edges by smoothing small variations.
Final output displays - Original Image,Grayscale Image,Blurred Image,Canny Edge Detected Image.
