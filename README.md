# README
# Object Classification Model Using YOLO and Image Processing

This project implements an object classification model that leverages both traditional image processing techniques and deep learning (YOLO-v8) to identify and classify objects in raw images. The model is designed to efficiently process raw image data and generate accurate predictions for various objects in real-world scenes.

## Features
- **Image Preprocessing**: Applied multiple image filtering techniques to enhance raw images.
  - MedianBlur
  - Bilateral filtering
  - Gaussian Blur
  - Fourier-based filters
- **Object Detection and Classification**: Trained a YOLO-v8 model for robust object classification and localization.
- **Accurate Predictions**: Achieved high precision and recall in identifying and classifying objects from images.

## Technologies Used
- **Deep Learning Framework**: YOLO-v8
- **Image Processing**: OpenCV for image filtering and enhancement
- **Programming Language**: Python
- **Other Libraries**: 
  - NumPy
  - pandas
  - Matplotlib for visualizations
  - Ultralytics for YOLO

## Model Architecture
- **Image Preprocessing**: 
  - Applied MedianBlur, Bilateral, and Gaussian filters to reduce noise and improve image quality.
  - Fourier-based filtering for frequency domain enhancements.
- **YOLO-v8**:
  - Utilized the YOLO-v8 architecture for real-time object detection.
  - Configured bounding boxes and class predictions using the YOLO head layer.

## Dataset
- The model was trained on a dataset of raw images containing objects from various categories. Each image was labeled with bounding boxes and class labels to facilitate training.

- **Preprocessing**: The raw images underwent several transformations including noise reduction and edge enhancement, which improved the model’s ability to detect objects in noisy and low-quality images.

## Results
- The YOLO-v8 model successfully generated accurate object predictions with high precision and recall. 
- The application of image filtering techniques prior to model training led to improvements in detection accuracy, especially for noisy or low-contrast images.


