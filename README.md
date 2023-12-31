﻿### SAM-with-Object-detection


The goal is to explore object detection with newly launch architecture of SAM which segment anything, it is an amazing development from facebook team. it has many way to gest your images segments the part that interest me the most is to give a specific bounding box, and then ask to segment using the SAM model. 


#### Yolov8 
Yolov8 is one of the latest model from the family of yolo, this latest one develop by the team of [ultralytics](https://docs.ultralytics.com/) and its performance is amazing. 

![SAM](yolov8.jpg)

### SAM 
SAM is the one of the latest development in the field of segmentations, this architecture has changed a lot things in the way we approach segmentations. it pretty much enable us not to train segmentation models if it is not neccesary to do so. you could give three different type of input to the SAM model, and it would segment it accordingly. 

![yolo](sam.png)


### Result of the Detection 
Here is the result of the detection from Yolov8. Given that the few amount of data, the detection is not really bad. 

![predicted](detected_data_using.jpeg)



### Result of the SAM 
Below is the results of Segmented part using SAM, and the calculated the void areas. 


![predicted](segmented_calculated.png)


## References:
1. https://github.com/ultralytics/ultralytics
2. https://blog.roboflow.com/whats-new-in-yolov8/
3. https://github.com/facebookresearch/segment-anything 
