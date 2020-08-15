# OpenCV
OpenCV tutorial

### OpenCV is a library of programming functions mainly aimed at real-time computer vision.
### First Image Show 
import numpy as np
>>> import cv2
>>> img = cv2.imread("opencv-logo.png")
>>> cv2.namedWindow("Image",cv2.WINDOW_NORMAL)
>>> cv2.imshow("Image",img)
>>> cv2.waitKey(0)
108
>>> cv2.imwrite("output.jpg",img)
True

### Access and Understand pixel data
 import numpy as np
>>> import cv2
>>> img = cv2.imread("opencv-logo.png",1)
>>> img
