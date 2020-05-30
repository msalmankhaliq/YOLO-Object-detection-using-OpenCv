# YOLO Object detection using deep learning with OpenCV

OpenCV `dnn` module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow. 

When it comes to object detection, popular detection frameworks are
 * YOLO
 * SSD
 * Faster R-CNN
 
 Support for running YOLO/DarkNet has been added to OpenCV dnn module recently. 
 
 ## Dependencies
  * opencv
  * numpy
  * imutils
  
`pip install numpy`
`pip install opencv`
`pip install imutils`

 ## YOLO (You Only Look Once)
 
 We are using YOLOv3, in particular, YOLO trained on the COCO dataset.
 
 ![coco dataset](https://github.com/msalmankhaliq/YOLO-Object-detection-using-OpenCv/blob/master/COCO.png.jpg)

The COCO dataset consists of 80 labels, including, but not limited to:
    People
    Bicycles
    Cars and trucks
    Airplanes
    Stop signs and fire hydrants
    Animals, including cats, dogs, birds, horses, cows, and sheep, to name a few
    Kitchen and dining objects, such as wine glasses, cups, forks, knives, spoons, etc.
    …and much more!

 Download the pre-trained YOLO v3 weights file from this [link](https://pjreddie.com/media/files/yolov3.weights) and place it in your jupyter notebook directory.
  
 Provided all the files are in the directory, apply object detection on the input image of your choice by running `object detection on image.ipynb` on jupyter notebook.
 After that, you'll get the output of a image with detected objects.
 
 If you want to run the model on a video then open `object detection on video.ipynb` on your jupyter notebook and input video of your choice then run it and wait for the execution to complete to get the output video with object detections.
 
 Checkout the [blog post](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/) to learn more.
 
### sample output on image  :
 
 ![Object detection on a image](https://github.com/msalmankhaliq/YOLO-Object-detection-using-OpenCv/blob/master/yolo_soccer_output.jpg)
 
### sample output on Video
 
[![Object detection on video](https://img.youtube.com/vi/QYV3S-WED4Q/hqdefault.jpg)](https://youtu.be/QYV3S-WED4Q)
 
 
 
 
###License

Licensed under the Apache License, Version 2.0. Copyright 2019.
