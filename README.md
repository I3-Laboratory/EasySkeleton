# EasySkeleton
This is an implementation of submitted paper:
Wenli Zhang, Xinyu Peng, Guoqiang Cui, Haozhou Wang, Daisuke Takata and Wei Guo, "Tree Branch Skeleton Extraction from Drone-Based Photogrammetric Point Cloud", Drones, vol. 2023,. 
This paper introduces a method to extract skeleton from RGB synthesized branch point cloud. You can use this procedure to extract skeleton from point cloud, and obtain the procedure from the [link]().

## Video demo
A quick video demo of the algorithm can be [found here](https://youtu.be/cq_7MVMzZ90).


## point cloud data pre-processing video demo
1. [orchard segmentation](https://www.youtube.com/embed/I48e63mNP0Y)

2. [tree segmentation](https://www.youtube.com/embed/KqyYVsdYSZg)



## Restrictions
- This procedure runs in win_x64.
- Currently, only ASCII encoded .ply file is supported, you can use other tools to convert point cloud formats, such as [CloudCompare](https://github.com/CloudCompare/CloudCompare).
- The file path should not contain Chinese characters.
- The branch point cloud size should be less than 20k points.
- The branch point cloud needs to be claer and its shape should be radial.

## Data and software avaible
You can obtain the sample point cloud data from the [link]().
