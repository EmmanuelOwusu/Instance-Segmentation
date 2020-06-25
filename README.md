# Instance-Segmentation
Project done in Instance Segmentation and Human pose estimation.

Instance segmentation requires the prediction of object instances and their per-pixel segmentation mask.

* This makes it a hybrid of semantic segmentation and object detection.

* I installed Detectron2 in google colab. I used pictures(images) from my personal
collections and on the internet and run a pre-trained model on them.

# Summary of Work

* Instance segmentation is a subtype of image segmentation which identifies each
instance of each object within the image at the pixel level.

* I used the Mask Regional Convolutional Neural Network (Mask R-CNN) method.
The framework of Mask R-CNN is based on two stages: first, it scans the im-
age to generate proposals; which are areas with a high likelihood to contain an
object. 

* Second, it classifies these proposals and creates bounding boxes and
masks.

* The backbone architecture used here is the ResNet-50 . The data set used is
the coco dateset.




## Important Information
----------------------------

    -Used Python Version: 3.6.0

    -install  modules with ```pip install detectron2``` command.
    
    -Run the file CV_2LAB_1 in colab or jupyter notebook.
    
 ------------------------------------------------------

