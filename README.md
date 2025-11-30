Bounding Box Object Detection
Experience real-time object detection with this computer vision project. 
Using OpenCV's powerful functions, I've crafted a system that creates dynamic bounding boxes around specific objects captured by my webcam.
In this unique application, the bounding box comes to life whenever a yellow object is detected in the camera's field of view.

​

Key Features:

Color-based Detection: The algorithm uses advanced color detection techniques, utilizing hue, saturation, and value parameters, to identify the presence of yellow objects.

OpenCV Integration: Leveraging OpenCV's VideoCapture for webcam access, cvtColor for efficient color space conversion (BGR to HSV), and inRange for precise color range identification.

Bounding Box Precision: I've implemented the PIL library's getbbox function to determine the exact coordinates of the smallest rectangle encapsulating the detected yellow object.
