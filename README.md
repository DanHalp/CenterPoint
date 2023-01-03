# Center-based 3D Object Detection and Tracking

3D Object Detection and Tracking using center points in the bird-eye view.

# CenterPoint

3D Object Detection and Tracking using center points in the bird-eye view.

This forked repo were used for the lecture Advanced Deep Learning for Computer Vision. Our poster and contributions:
![Team2_cvpr_poster](https://user-images.githubusercontent.com/20690194/203155410-92ceca31-5006-4ae0-a3a9-6a3d89c0f1aa.png)

Click here for the [Final Project Report](https://github.com/DanHalp/CenterPoint/blob/master/Final%20Report.pdf)

## Reference papers \ Repos:
1) Center Point: https://arxiv.org/abs/2006.11275
2) BiFPN horizon Robotics: https://arxiv.org/abs/2006.15505
3) BiFPN GitHub Repo: https://github.com/ViswanathaReddyGajjala/EfficientDet-Pytorch
4) Metrics GitHub repo: https://github.com/rafaelpadilla/Object-Detection-Metrics

GCP VM Settings:
- Intel N1-highmem-4 (4vCPU, 26 GB Memory)
- Nvidia Tesla T4
- 500 GB SSD

Useful Links:
1) GCP GPU Zones: https://cloud.google.com/compute/docs/gpus/gpu-regions-zones

## Original Abstract
Three-dimensional objects are commonly represented as 3D boxes in a point-cloud. This representation mimics the well-studied image-based 2D bounding-box detection but comes with additional challenges. Objects in a 3D world do not follow any particular orientation, and box-based detectors have difficulties enumerating all orientations or fitting an axis-aligned bounding box to rotated objects. In this paper, we instead propose to represent, detect, and track 3D objects as points. Our framework, CenterPoint, first detects centers of objects using a keypoint detector and regresses to other attributes, including 3D size, 3D orientation, and velocity. In a second stage, it refines these estimates using additional point features on the object. In CenterPoint, 3D object tracking simplifies to greedy closest-point matching. The resulting detection and tracking algorithm is simple, efficient, and effective. CenterPoint achieved state-of-the-art performance on the nuScenes benchmark for both 3D detection and tracking, with 65.5 NDS and 63.8 AMOTA for a single model. On the Waymo Open Dataset, CenterPoint outperforms all previous single model method by a large margin and ranks first among all Lidar-only submissions.
