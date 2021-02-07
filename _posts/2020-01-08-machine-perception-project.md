---
title: 'LiDAR sensor data fusion'
categories:
  - projects
tags:
  - sensor fusion
  # - MSc. Robotics
  - LiDAR
  - Python
image: 
  path: /assets/images/MP_grid_vid.gif
  thumbnail: /assets/images/MP_grid_vid.gif
  caption: "test"
---

For this project the pointcloud data of a lidar was fused with the pointclouds obtained from a stereo camera. The data required a lot of preprocessing for it to be usable. For example the egomotion of the moving vehicle had to be compensated. Some other examples are the non synchronous arrival of the different sensor modalities or the RANSAC algorithm which was applied to remove the ground plane


![demo lidar vs stereo](/assets/images/top_view_lidarvsstereo.png)
in this image you see the 2 distinct pointclouds. In green the LiDAR pointcloud and in grey (actually RGB) the stereo camera pointcloud.


![demo vid](/assets/images/MP_grid_vid.gif)
In this video you can see the occupancy grid which was constructed from the pointcloud data.