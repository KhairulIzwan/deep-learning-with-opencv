# deep-learning-with-opencv

Build on:

1. Python 2.7.12
2. OpenCV 3.3.1-dev (as pre-installed with ROS-Kinetic)

Scripts:

1. **deep_learning_with_opencv.py**:

using pre-trained deep learning models - OpenCV 3.3’s deep neural network (dnn ) module.

> python deep_learning_with_opencv.py --image download.jpeg --prototxt bvlc_googlenet.prototxt --model bvlc_googlenet.caffemodel --labels synset_words.txt 

2. **deep_learning_object_detection.py**:

apply object detection using deep learning and OpenCV

> python deep_learning_object_detection.py --prototxt MobileNetSSD_deploy.prototxt --model MobileNetSSD_deploy.caffemodel --image file_23012_beagle-460x290.jpg

3. **deep_learning_realtime_object_detection.py**:

apply deep learning-based object detection to real-time video streams using OpenCV and Python

> python deep_learning_realtime_object_detection.py --prototxt MobileNetSSD_deploy.prototxt --model MobileNetSSD_deploy.caffemodel

4. **deep_learning_face_detection.py** [FAILED]

> still searching for a solution -- available solution currently works on OpenCV > 3.3
