---
title: '3D Sensor Data Fusion'
# categories:
#   - projects
# tags:
#   - Sensor Fusion
#   - Uni Project
#   - LiDAR
#   - Python
img: /assets/img/MP_grid_vid.gif
# image: 
#   path: /assets/img/MP_grid_vid.gif
#   thumbnail: /assets/img/MP_grid_vid.gif
#   caption: "test"
---

For this project the pointcloud data of a LiDAR was fused with the pointclouds obtained from a stereo camera. The data required a lot of preprocessing for it to be usable. First the egomotion of the moving vehicle had to be compensated. Some other challenges were the non-synchronous arrival of the different sensor modalities, or the removal of the ground plane for which the [RANSAC algorithm](https://en.wikipedia.org/wiki/Random_sample_consensus) was employed.


![demo lidar vs stereo](/assets/img/top_view_lidarvsstereo.png)
*figure 1: in this image you see the 2 distinct pointclouds. In green the LiDAR pointcloud and in grey (actually RGB) the stereo camera pointcloud.*


![demo vid](/assets/img/MP_grid_vid.gif)
*figure 2: In this video you can see the occupancy grid which was constructed from the pointcloud data.*