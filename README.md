# Object-Detection-MobileNet
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)<br><br>
Demonstration of Object Detection using MobileNets and OpenCV. 
## Description
This project was made for detecting 20 different types of object such as "background", "aeroplane", "bicycle", "bird", "boat",
           "bottle", "bus", "car", "cat", "chair", "cow", "diningtable",
           "dog", "horse", "motorbike", "person", "pottedplant", "sheep",
           "sofa", "train", "tvmonitor" in a live video using the webcam or a pre-recorded video.<br>
## Preview
![Alt Text](https://github.com/Sid2697/Object-Detection-MobileNet/blob/master/Object_Detection.gif)
### Better Quality Video
[![IMAGE ALT TEXT](https://github.com/Sid2697/Object-Detection-MobileNet/blob/master/Thumbnail.png)](https://youtu.be/gcw4lQFYXO0)

## Requirements
- numpy
- imutils
- OpenCV

You can install all the required libraries by running the following command <br>
`pip install requirements.txt`
## Functionalities
1. Using pre-trained [MobileNet](https://arxiv.org/abs/1704.04861) architecture for detection of the objects present.
2. Combining MobileNet and Single Shot Detector(SSD) framework.
3. Model used is Caffe version of original [TensorFlow implementation](https://github.com/Zehaos/MobileNet) by Howard et al. 
## Procedure
### For detecting objects in an image.
```bash
./image_object_detection.py -i #path to the input image -p #path to Caffe deploy prototxt file -m #path to the Caffe pre-trained model
```
### For detecting objects in a video.
```bash
./video_object_detection.py -p #path to Caffe deploy prototxt file -m #path to the Caffe pre-trained model
```
## Credits
Adrian Rosebrock creator of [PyimageSearch](https://www.pyimagesearch.com) 
