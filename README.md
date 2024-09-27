# Helmet_Detection_Yolov8m
This repository contains the implementation of a Helmet Detection System using the YOLOv8m (You Only Look Once - version 8 medium) object detection model. The goal of this project is to automatically detect and classify whether a person is wearing a helmet in an image or video feed or real-time webcam.
This system enables cv to detect whether a person wears helmet or not with high confidence probability.

STEPS TO ACCESS THE CODE : 
1. Follow the directory structure attached as a text file - [directorystructure.txt]
2. Download and extract the dataset from Kaggle - [Link] - kaggle datasets download -d andrewmvd/hard-hat-detection - https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection/data
3. As per the directory structure attach the annotations and images file in the dataset.
4. Ensure the paths in the pynb training file.
5. data.yaml should be updated with absolute path for train test and val.
6. Command for prediction on real time webcam: !yolo task=detect mode=predict model=runs/detect/train3/weights/best.pt source=0
7. Command for prediction on mp4 files : !yolo task=detect mode=predict model=runs/detect/train3/weights/best.pt source=test.mp4

This system enables for real time helmet detection trained using custom dataset yolov8m model.
- [ Raghu dharsan ]
- [ raghudharsan324@gmail.com ]
