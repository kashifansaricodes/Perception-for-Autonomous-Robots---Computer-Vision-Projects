# ENPM673 Perception for Autonomous Robots - Computer Vision Projects

This repository contains three computer vision projects completed as part of the ENPM673 Perception for Autonomous Robots course. Each project focuses on different aspects of computer vision and image processing techniques.

## Repository Structure

```bash
.
├── Project1/
│   ├── object_tracking/
│   └── README.md
├── Project2/
│   ├── corner_detection/
│   ├── panorama_stitching/
│   └── README.md
├── Project3/
│   ├── camera_calibration/
│   ├── stereo_vision/
│   └── README.md
└── README.md
```

## Projects Overview

### Project 1: Object Tracking and Curve Fitting
Implementation of an object detection and tracking system for analyzing the trajectory of a black object thrown against a wall.

#### Key Features
- Frame extraction using OpenCV
- Color-based object detection
- Centroid calculation
- Parabolic curve fitting using Standard Least Squares
- Trajectory visualization

For detailed information, see [Project1/README.md](./Project1/README.md).

### Project 2: Corner Detection and Image Stitching
A two-part project focusing on advanced image processing techniques.

#### Part 1: Paper Corner Detection
- Blur detection using Variance of Laplacian
- Edge detection and line detection with Hough Transform
- Corner detection and verification
- Visual overlay of boundaries and corners

#### Part 2: Panoramic Image Stitching
- Feature extraction and matching
- RANSAC-based homography computation
- Image warping and blending for panorama generation

For detailed information, see [Project2/README.md](./Project2/README.md).

### Project 3: Camera Calibration and Stereo Vision
Comprehensive implementation of camera calibration and stereo vision systems.

#### Part 1: Single Camera Calibration
- Chessboard/circular pattern detection
- Camera parameter optimization
- Reprojection error analysis

#### Part 2: Stereo Vision System
- Feature matching between stereo images
- Fundamental and Essential matrix computation
- Image rectification, disparity map generation, and depth computation

For detailed information, see [Project3/README.md](./Project3/README.md).

## Technical Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab (for development and testing)

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
This repository is for educational purposes and demonstrates various computer vision concepts and implementations.
