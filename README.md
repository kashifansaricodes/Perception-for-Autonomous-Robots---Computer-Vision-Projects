# ENPM673 Perception for Autonomous Robots - Computer Vision Projects

This repository contains computer vision projects completed as part of the tools: Perception for Autonomous Robots. The repository includes four projects focusing on different aspects of computer vision and image processing techniques.

## Repository Structure
```bash
.
├── Project1/
│   └── object_tracking/
├── Project2/
│   ├── corner_detection/
│   └── panorama_stitching/
├── Project3/
│   ├── camera_calibration/
│   └── stereo_vision/
├── Project4/
│   ├── image_enhancement/
│   ├── convolution_analysis/
│   └── practical_applications/
└── README.md
```

## Projects Overview

### Project 1: Object Tracking and Curve Fitting
Implementation of an object detection and tracking system for analyzing the trajectory of a black object thrown against a wall.
- Frame extraction using OpenCV
- Color-based object detection
- Centroid calculation
- Parabolic curve fitting using Standard Least Squares
- Trajectory visualization

### Project 2: Corner Detection and Image Stitching
A two-part project focusing on advanced image processing techniques.
- Part 1: Paper Corner Detection
  - Blur detection using Variance of Laplacian
  - Edge detection and line detection with Hough Transform
  - Corner detection and verification
  - Visual overlay of boundaries and corners
- Part 2: Panoramic Image Stitching
  - Feature extraction and matching
  - RANSAC-based homography computation
  - Image warping and blending for panorama generation

### Project 3: Camera Calibration and Stereo Vision
Comprehensive implementation of camera calibration and stereo vision systems.
- Part 1: Single Camera Calibration
  - Chessboard/circular pattern detection
  - Camera parameter optimization
  - Reprojection error analysis
- Part 2: Stereo Vision System
  - Feature matching between stereo images
  - Fundamental and Essential matrix computation
  - Image rectification, disparity map generation, and depth computation

### Project 4: Advanced Image Processing and Computer Vision Applications
This project explores various fundamental and advanced computer vision techniques:
- Part 1: Image Enhancement Techniques
  - Color space transformations
  - Histogram equalization implementation
  - Gamma correction for dark image enhancement
- Part 2: Convolution Analysis and Optimization
  - Big O notation analysis for convolution operations
  - Separable kernel concepts and implementations
  - Kernel decomposition techniques
- Part 3: Practical Computer Vision Applications
  - PCA-based ellipse fitting and surface analysis
  - Train track detection and distance measurement
  - Vehicle surround view system design and sensor configuration

## Technical Requirements
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab (for development and testing)
- Additional libraries: plotly, pandas

## Installation and Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/ENPM673-CV-Projects.git
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Note
This repository is for educational purposes and demonstrates various computer vision concepts and implementations. Each project builds upon previous concepts while introducing new techniques and applications. For specific project details, please refer to the individual README files in each project directory.
