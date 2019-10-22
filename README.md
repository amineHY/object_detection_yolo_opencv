# Description

This repository contains code of object detection application using `YOLO` model from darknet with `dnn` module of `OpenCV`


# Usage


* input image: 
```bash
python3 object_detection_yolo.py --label=coco.names --cfg=yolov3-tiny.cfg --model=yolov3-tiny.weights --image=fire.jpg
```

* input video: 
```bash 
python3 object_detection_yolo.py --label=coco.names --cfg=yolov3-tiny.cfg --model=yolov3-tiny.weights --video=fire.mp4
```

* webcam: 
``` 
bash python3 object_detection_yolo.py --label=coco.names --cfg=yolov3-tiny.cfg --model=yolov3-tiny.weights
```


# Fire detection 

A YOLO model for fire detection is provided in the folder `models`, you can use similar to above:

* input image: 
```
bash python3 object_detection_yolo.py --label=obj.names --cfg=yolov3-tiny-obj.cfg --model=yolov3-tiny-obj_final.weights --image=fire.jpg
```

* input video: 

```bash 
python3 object_detection_yolo.py --label=obj.names --cfg=yolov3-tiny-obj.cfg --model=yolov3-tiny-obj_final.weights  --video=fire.mp4
```

* webcam: 
```bash 
python3 object_detection_yolo.py --label=obj.names --cfg=yolov3-tiny-obj.cfg --model=yolov3-tiny-obj_final.weights
``` 


# Reference 
* Original website: [https://pjreddie.com/darknet/yolo/](https://pjreddie.com/darknet/yolo/)