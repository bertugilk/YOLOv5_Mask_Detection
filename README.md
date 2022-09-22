# YOLOv5_Mask_Detection
I trained a mask dataset on the roboflow website using the YOLOv5 algorithm and successfully obtained a working mask detection model.

## Installation

!git clone https://github.com/ultralytics/yolov5  # clone repo <br />
%cd yolov5 <br />
%pip install -qr requirements.txt # install dependencies

## Run
python detect.py --weights ../weights/best.pt --img 416 --conf 0.4 --source 0 <br />

![val_batch0_labels](https://user-images.githubusercontent.com/48621020/191825468-5c49f00a-0445-4bf8-8639-3a17278fd2e5.jpg)
