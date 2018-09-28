# Object-Recognition

About TensorFlow Object Detection API :
This API can be used to detect, with bounding boxes, objects in images and/or video using either some of the pre-trained models made available or through models you can train on your own (which the API also makes easier).

This code is implemented using the Tensorflow Object Detection API. There are two implementations, one is the webcam streaming version the other one is a video-input version.

Requirements:
1. tensorflow
2. cv2
3. matplotlib
4. PIL

To run:
1. git clone repository
2. install all the dependencies
3. run $python object_detection_webcam.py  #for streaming from your webcam
4. run $python object_detection_video.py  #for video-input
