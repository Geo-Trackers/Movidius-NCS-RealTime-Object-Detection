# Movidius-NCS-RealTime-Object-Detection
This repository contains necessary python scripts, models for enabling real-time object detection on Raspberry Pi using Movidius Neural Compute Stick. 

This script (object-detection.py) performs object detection in real-time on Raspberry Pi 3 and Pi Camera using Movidius Neural Compute Stick.For the image classification, we applied MobileNet neural network and for the object detection we applied Single Shot Multibox Detector as our object detection algorithm which was trained on MS-COCO dataset by chuanqui305, https://github.com/chuanqi305/MobileNet-SSD


Example USAGE: 

python object-detection.py --graph graph --display 1

To display objects above the threshold 50%, we could specify --confidence 0.5 as below

 python object-detection.py --graph graph --confidence 0.5 --display 1




![](https://user-images.githubusercontent.com/7304644/44517484-8e4f0680-a6e7-11e8-9d5a-d0d29223626e.jpg,width="545")



<a href="https://www.youtube.com/embed/LeC3KNHD_XA
" target="_blank"><img src="https://user-images.githubusercontent.com/7304644/44517278-010bb200-a6e7-11e8-9739-8c283dcd42db.png" 
alt="Demonstration of Object-Detection using Raspberry Pi & NCS" width="1440" border="10" /></a>




This has been referenced from www.pyimagesearch.com, and the credit goes to Adrian Rosebrock.
