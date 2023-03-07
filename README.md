Deep learning in mammography to detect abnormality breast cancer tissue

Project definition
Breast cancer is one of the most common cancers that happen to women. The rule for diagnosis is based on the analysis of mammographic images, but the accuracy is always limited by doctors’ experience and skills. In this paper, we will explore multiple neural networks models to improve the detection accuracy, and compare the performances among these approaches.

Approach to the project
Extract images from the mini MIAS database. Since the bounding boxes are using x, y, and radius, pre-process the coordinate to YOLO format is needed.
Use some data augmentation techniques for removing noise from images along with horizontal flipping, zooming, etc. 
YOLOv5 and Retinanet are implemented.

How to use the files
Preprocess.ipynb is for preprocess images
Augmentation.ipynb is for the image augmentation
YOLOv5_Custom_Training.ipynb is for training yolo model
RetinaNet_MIAS.ipynb is for training Retinanet model
