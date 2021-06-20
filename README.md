# mediapipe_hand
mediapipe developed by Google is a useful library for detecting the target objects including hands, faces, iris, pose...

This repository shows how to install and use mediapipe for locating fingers of a hand in 2D-dimension.

# How to install mediapipe

tensorflow and opencv library must be installed before installing mediapipe.

$ pip install tensorflow

$ pip install opencv-python

$ pip install mediapipe

# How to run finger.py

A hand can be detected and 21 points of five fingers can be generated:

<img src="hand.png" height=260 width=770 >

handLandmarks[4][1] indicates Thumb-finger-tip of x-axis.

handLandmarks[8][2] indicates Index-finger-tip of y-axis.

What is handLandmarks[20][2]?

$ python finger.py
