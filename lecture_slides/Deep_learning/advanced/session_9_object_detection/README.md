# Additional Study Material
P. Viola and M. J. Jones, "Rapid Object Detection using a Boosted Cascade of Simple Features," CVPR 2001.
The Viola-Jones algorithm introduced a real-time face detection method using a cascade of simple Haar-like features.
Histogram of Oriented Gradients (HOG):

N. Dalal and B. Triggs, "Histograms of Oriented Gradients for Human Detection," CVPR 2005.
HOG algorithm extracts image features based on the distribution of gradient orientations, widely used for pedestrian detection.
Deformable Part Models (DPM):

P. F. Felzenszwalb et al., "Deformable Part Models," CVPR 2008.
DPM introduced a framework for object detection that models objects as a collection of deformable parts, achieving state-of-the-art performance.
R-CNN:

R. Girshick et al., "Rich feature hierarchies for accurate object detection and semantic segmentation," CVPR 2014.
R-CNN proposed using a region proposal algorithm and a CNN to detect objects, improving accuracy and enabling object segmentation.
Fast R-CNN:

R. Girshick, "Fast R-CNN," ICCV 2015.
Fast R-CNN improved upon R-CNN by introducing a region of interest pooling layer, enabling faster training and testing.
Faster R-CNN:

S. Ren et al., "Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks," NeurIPS 2015.
Faster R-CNN introduced a region proposal network (RPN) that shares convolutional features, enabling end-to-end object detection in real-time.
YOLO:

J. Redmon et al., "You Only Look Once: Unified, Real-Time Object Detection," CVPR 2016.
YOLO formulates object detection as a regression problem, predicting class labels and bounding box coordinates directly from the input image, achieving real-time performance.
SSD:

W. Liu et al., "SSD: Single Shot MultiBox Detector," ECCV 2016.
SSD utilizes multiple feature maps at different scales to detect objects of various sizes, achieving high accuracy in a single shot.
RetinaNet:

T.-Y. Lin et al., "Focal Loss for Dense Object Detection," ICCV 2017.
RetinaNet introduced the focal loss, addressing class imbalance and improving the detection of rare objects in dense object detection.
EfficientDet:

M. Tan et al., "EfficientDet: Scalable and Efficient Object Detection," CVPR 2020.
EfficientDet achieves state-of-the-art performance through compound scaling and efficient network architecture design, scalable for different object detection tasks.
DETR:

N. Carion et al., "End-to-End Object Detection with Transformers," ECCV 2020.
DETR introduced a transformer-based architecture for object detection, eliminating the need for anchor-based methods and achieving competitive results.

CornerNet:

He, K., Gkioxari, G., Dollár, P., & Girshick, R. (2018). "CornerNet: Detecting Objects as Paired Keypoints." ECCV 2018.
CornerNet introduces a keypoint-based object detection framework that detects objects by representing them as paired keypoints and regresses their bounding boxes.
CenterNet:

Zhou, X., Wang, D., & Krähenbühl, P. (2019). "Objects as Points." arXiv preprint arXiv:1904.07850 (2019).
CenterNet presents an approach that models objects as single points and performs object detection by directly regressing the center points and other object attributes.