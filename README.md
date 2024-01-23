# Multi Agent SLAM

In this report, we showcase our study on SLAM algorithms and Multi Agent SLAM algorithms. And explain the key components that are necessary to make SLAM algorithm into a Multi SLAM algorithm.

Next, we took an open source SLAM algorithim i.e., [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) and rewrite the backend with GTSAM and added SOTA algorithms for post graph optimization ([Graduated Non-Convexity](https://arxiv.org/abs/1909.08605)) and visual place recognition/loop closure detection ([NetVLAD](https://arxiv.org/abs/1511.07247)) and created a Multi agent framework. We discussed about our implementation Multi Agent SLAM algorithm, design choices for it and results in the report.

This work is part of DRDO funded project.

Click [here](https://github.com/devapi016/VINS-Mono-GTSAM) for the code.