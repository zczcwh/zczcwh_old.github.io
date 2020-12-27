---
title: "LodoNet: A Deep Neural Network with 2D Keypoint Matching for 3D LiDAR Odometry Estimation"
collection: publications
permalink: /publication/LodoNet
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2020-08-28
venue: "ACM Multimedia 2020"
paperurl: https://arxiv.org/abs/2009.00164"
citation: '<b>Ce Zheng</b>, Yecheng Lyu, Ming Li, Ziming Zhang. "LodoNet: A Deep Neural Network with 2D Keypoint Matching for 3D LiDAR Odometry Estimation". <i>(ACM Multimedia 2020)</i>. '
---
# LodoNet: A Deep Neural Network with 2D Keypoint Matching for 3D LiDAR Odometry Estimation

[<a href="https://arxiv.org/abs/2009.00164">Paper</a>]



## Abstract
Deep learning based LiDAR odometry (LO) estimation attracts
increasing research interests in the field of autonomous driving and
robotics. Existing works feed consecutive LiDAR frames into neural
networks as point clouds and match pairs in the learned feature
space. In contrast, motivated by the success of image based feature
extractors, we propose to transfer the LiDAR frames to image space
and reformulate the problem as image feature extraction. With
the help of scale-invariant feature transform (SIFT) for feature
extraction, we are able to generate matched keypoint pairs (MKPs)
that can be precisely returned to the 3D space. A convolutional
neural network pipeline is designed for LiDAR odometry estimation
by extracted MKPs. The proposed scheme, namely LodoNet, is then
evaluated in the KITTI odometry estimation benchmark, achieving
on par with or even better results than the state-of-the-art.

## Citation
    @article{zheng2020lodonet,
      title={LodoNet: A Deep Neural Network with 2D Keypoint Matchingfor 3D LiDAR Odometry Estimation},
      author={Zheng, Ce and Lyu, Yecheng and Li, Ming and Zhang, Ziming},
      journal={arXiv preprint arXiv:2009.00164},
      year={2020}
    }
