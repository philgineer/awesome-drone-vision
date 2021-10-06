# Awesome Drone Vision
- Models
  - [Object Detection](#object-detection-models)
  - [Object Tracking](#object-tracking-models)
  - [Segmentation](#segmentation-models)
- [Datasets](#datasets)

## Object Detection Models
- YOLO
  - YOLOv1 (You Only Look Once: Unified, Real-Time Object Detection) (2015) [[paper]](https://arxiv.org/abs/1506.02640)
  - YOLOv2 (YOLO9000: Better, Faster, Stronger) (2016) [[paper]](https://arxiv.org/abs/1612.08242)
  - YOLOv3: An Incremental Improvement (2018) [[paper]](https://arxiv.org/abs/1804.02767)
  - YOLOv4: Optimal Speed and Accuracy of Object Detection (2020) [[paper]](https://arxiv.org/abs/2004.10934) [[github]](https://github.com/AlexeyAB/darknet)
  - YOLOv5 (2020) [[github]](https://github.com/ultralytics/yolov5)
- SSD
  - SSD: Single Shot MultiBox Detector (2016) [[paper]](https://arxiv.org/abs/1512.02325)
- Anchor-free models
  - YOLOX: Exceeding YOLO Series in 2021 [[paper]](https://arxiv.org/abs/2107.08430)
  - FCOS: Fully Convolutional One-Stage Object Detection (2019) [[paper]](https://arxiv.org/abs/1904.01355)
  - ATSS (Bridging the Gap Between Anchor-based and Anchor-free Detection via Adaptive Training Sample Selection) (2021) [[paper]](https://arxiv.org/abs/1912.02424)
- SBS
  - Object Detection in Drone Imagery via Sample Balance Strategies and Local Feature Enhancement (2021) [[paper]](https://www.mdpi.com/2076-3417/11/8/3547)
- ZoomInNet
  - ZoomInNet: A Novel Small Object Detector in Drone Images with Cross-Scale Knowledge Distillation (2021) [[paper]](https://www.mdpi.com/2072-4292/13/6/1198)

## Object Tracking Models
- FairMOT: On the Fairness of Detection and Re-Identification in Multiple Object Tracking (2020) [[paper]](https://arxiv.org/abs/2004.01888) [[github]](https://github.com/ifzhang/FairMOT)
- SORT
  - SORT (Simple Online and Realtime Tracking) (2016) [[paper]](https://arxiv.org/abs/1602.00763) [[github]](https://github.com/abewley/sort)
  - DeepSORT (Simple Online and Realtime Tracking with a Deep Association Metric) (2017) [[paper]](https://arxiv.org/abs/1703.07402) [[github]](https://github.com/nwojke/deep_sort)

## Segmentation Models
- SegNet
  - SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation (2015) [[paper]](https://arxiv.org/abs/1511.00561)
- DeepLab
  - DeepLab V3 (Rethinking Atrous Convolution for Semantic Image Segmentation) (2017) [[paper]](https://arxiv.org/abs/1706.05587) [[github]](https://github.com/pytorch/vision/blob/master/torchvision/models/segmentation/deeplabv3.py)
  - DeepLab V3+ (Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation) (2018) [[paper]](https://arxiv.org/abs/1802.02611)
- Crack segmentation
  - CrackNet (Automated pixel-level pavement crack detection on 3D asphalt surfaces using a deep-learning network) (2017) [[paper(paid)]](https://onlinelibrary.wiley.com/doi/abs/10.1111/mice.12297)
  - CrackNet-V (Pixel-level cracking detection on 3D asphalt pavement images through deep-learning-based CrackNet-V) (2019) [[paper(paid)]](https://ieeexplore.ieee.org/document/8620557)
  - DeepCrack: A deep hierarchical feature learning architecture for crack segmentation (2019) [[paper]](https://github.com/yhlleo/DeepCrack/blob/master/paper/DeepCrack-Neurocomputing-2019.pdf) [[github]](https://github.com/yhlleo/DeepCrack)
  - SDDNet: Real-Time Crack Segmentation (2019) [[paper]](https://ieeexplore.ieee.org/abstract/document/8863123)
  - SCCDNet: A Pixel-Level Crack Segmentation Network (2021) [[paper]](https://www.mdpi.com/2076-3417/11/11/5074) [[github]](https://github.com/543630836/SCCDNet_crack)
- Unet
  - U-Net: Convolutional Networks for Biomedical Image Segmentation (2015) [[paper]](https://arxiv.org/abs/1505.04597)
  - UNet++: A Nested U-Net Architecture for Medical Image Segmentation (2018) [[paper]](https://arxiv.org/abs/1807.10165)
  - IterNet: Retinal Image Segmentation Utilizing Structural Redundancy in Vessel Networks (2019) [[paper]](https://arxiv.org/abs/1912.05763) [[github]](https://github.com/conscienceli/IterNet)

## Datasets
- Drone
  - VisDrone (2019) [[github]](https://github.com/VisDrone/VisDrone-Dataset) [[home]](http://aiskyeye.com/) [[paper]](https://arxiv.org/abs/2001.06303)
  - UAVDT (2018) [[home]](https://sites.google.com/view/grli-uavdt/%E9%A6%96%E9%A1%B5) [[paper]](https://arxiv.org/abs/1804.00518)
  - UAV-Human (2021) [[github]](https://github.com/SUTDCV/UAV-Human) [[paper]](https://arxiv.org/abs/2104.00946)
- Crack
  - CCIC (Concrete Crack Images for Classification) (2019) [[home]](https://data.mendeley.com/datasets/5y9wdsg2zt/2)
  - SDNET2018: A concrete crack image dataset for machine learning applications [[home]](https://digitalcommons.usu.edu/all_datasets/48/)
- Object Tracking
  - MOT (Multiple Object Tracking) [[home]](https://motchallenge.net/)
  - VOT (visual object tracking) [[home]](https://votchallenge.net/)
