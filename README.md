# Numpy-Program
All program includeed numpy, cv2 and etc




# Getting Started with Videos
## Goal
* Learn to read video, display video and save video.
* Learn to capture from Camera and display it.
* You will learn these functions : cv2.VideoCapture(), cv2.VideoWriter()
Capture Video from Camera
Often, we have to capture live stream with camera. OpenCV provides a very simple interface to this. Let’s capture a video from the
camera (I am using the in-built webcam of my laptop), convert it into grayscale video and display it. Just a simple task to get started.

To capture a video, you need to create a VideoCapture object. Its argument can be either the device index or the name of a video file. 
Device index is just the number to specify which camera. Normally one camera will be connected (as in my case). 
So I simply pass 0 (or -1).
You can select the second camera by passing 1 and so on. After that, you can capture frame-by-frame. But at the end,
don’t forget to release the capture.
