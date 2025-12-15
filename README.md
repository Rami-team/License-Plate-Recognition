# License Plate Recognition

This project implements a License Plate Recognition (LPR) system using computer vision and optical character recognition (OCR).
The goal is to automatically detect vehicle license plates from images and extract the plate text.

##  Project Overview
License Plate Recognition is an important application in intelligent transportation systems, traffic monitoring, and automation.
This project uses classical image processing techniques combined with OCR to identify license plate characters.

##  Technologies Used
- Python
- OpenCV
- EasyOCR
- NumPy
- Matplotlib
- imutils

##  How It Works
1. Load the input image
2. Convert the image to grayscale
3. Apply filtering and edge detection
4. Detect contours to localize the license plate
5. Extract the license plate region
6. Apply OCR to read the characters
7. Display and save the results
