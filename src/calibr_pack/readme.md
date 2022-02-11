# the node do the calibration

we have load **a mono camera** , a Intel **Realsense D435 camera** and **a checker pattern** in another pack. In the realsense_ros_gazebo pack.

in this pack

```
input:
1. stereo image
2. mono image
3. point cloud (created by stereo image)
```

```
output:
extrinsic between
mono camera   《------》  D435 camera
```

```c++
/// @todo 
1. which in the center of D435 ?
2. calibration process online or offline ?
3. what kind of features been applied in the calibration process
    3.1 points ?
    3.2 lines ?
```

