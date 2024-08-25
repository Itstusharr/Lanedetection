# Lanedetection
 This project involves the implementation of a lane detection system using computer vision techniques. The system processes video frames to identify lane markings on the road. The primary steps include:

Edge Detection: Using the Canny edge detection algorithm to identify edges in the image.
Region of Interest: Defining a region of interest to focus on the relevant part of the image, which is typically the area where lane lines are expected.
Hough Transform: Applying the Hough Transform to detect lines within the edges.
Lane Identification: Averaging the slopes and intercepts of the detected lines to identify the left and right lanes.
Key Features
Edge Detection with Canny: Converts the input image to grayscale, applies Gaussian blur, and then detects edges using the Canny method.
Hough Transform: Finds lines in the edge-detected image using the Hough Transform, which is then averaged and filtered to identify lane lines.
Dynamic Lane Adjustment: Automatically adjusts the detected lanes based on the road curvature and camera perspective.
This project is ideal for understanding basic lane detection in autonomous driving systems. It can be further extended to include advanced techniques, such as using neural networks for more robust detection and sensor fusion to enhance accuracy.
