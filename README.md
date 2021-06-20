# mediapipe_hand
mediapipe developed by Google is a useful library for detecting the target objects including hands, faces, iris, pose...

This repository shows how to install and use mediapipe for locating fingers of a hand in 2D-dimension: x-axis and y-axis coordinates.

# How to install mediapipe

tensorflow and opencv library must be installed before installing mediapipe.

$ pip install tensorflow

$ pip install opencv-python

$ pip install mediapipe

# How to run finger.py

A hand can be detected and 21 points of five fingers can be generated:

<img src="hand.png" height=260 width=770 >

handLandmarks[ ][ ] can identify a position of 21 points by the first index and an axis of x or y by the second index.

handLandmarks[4][1] indicates Thumb-finger-tip "4" of x-axis "1".

handLandmarks[8][2] indicates Index-finger-tip "8" of y-axis "2".

What is handLandmarks[20][2]?

$ python finger.py

# Exercises for students

Build a stone-paper-scissors or rock-paper-scissors detection system.

