# Occluded Object Detection

The whole idea of the project is to detect an object whether it is covered by any obstacle or clearly visible. We propose a solution using a combination of Deep-Mask and YOLOv2.

YOLOv2 or such similar networks are good for complete object detection, whereas Mask-RCNN model is good in segment detection, therefore a combination of these can be used for detection of an occluded object.

Incase where multiple objects exists overlapping each other, Depth images can be used to find which object is on top/front of another object.

## Dataset

Mask-RCNN and YOLOv2, both networks were trained on [Microsoft Kinet RGB-D](http://rgbd-dataset.cs.washington.edu/index.html) dataset containing 548 images of a Coffee Cup.


## Weights and data in [drive](https://drive.google.com/drive/folders/1el40zrXsojGhmhtIqRa2c_Wjm6uC9HuY?usp=share_link)
