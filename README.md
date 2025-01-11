# (Robot Perception) Object Tracking and Curve Fitting

## Overview
Implementation of an object detection and tracking system that analyzes the trajectory of a black object thrown against a wall.

## Project Objectives
1. Extract video frames using OpenCV
2. Detect moving black object using color-based segmentation
3. Calculate object centroids in each frame
4. Fit a parabolic curve using the Standard Least Squares method
5. Predict y-axis value for x=1000
6. Visualize results on video frames

## Implementation Details

### Video Processing Pipeline
1. **Frame Extraction**
   - OpenCV for reading video frames
   - No built-in functions allowed except for basic I/O

2. **Object Detection**
   - Color-based pixel extraction
   - Custom implementation without built-in functions
   - Numpy-based operations

3. **Centroid Calculation**
   - Custom centroid calculation algorithm
   - Frame-by-frame processing
   - Top-left corner as origin (0,0)

4. **Curve Fitting**
   - Standard Least Squares implementation
   - Parabolic curve fitting
   - Custom mathematical implementation

## Project Constraints
- OpenCV usage limited to:
  - Video frame access
  - Frame display
  - Video/frame saving
- No built-in functions for:
  - Object detection
  - Centroid calculation
  - Curve fitting

## Usage
1. Run the notebook in Google Colab
2. Upload the provided video
3. Execute all cells sequentially
4. Results include:
   - Detected object visualization
   - Centroid tracking
   - Fitted parabolic curve
   - Y-axis prediction for x=1000

## Technical Requirements
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab
