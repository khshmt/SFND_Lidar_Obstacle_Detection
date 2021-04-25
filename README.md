# Udacity Sensor Fusion Engineer Nanodegree.
## Lidar module.
this repository contains the solutions of all the assignments and the quiz plus the solution of the project of the lidar module implemented using the **PCL library function**.

---
## Minimum prerequisites.
1. **ubuntu 16.04.**
1. **g++-5.5.**
2. **PCL 1.2 library.** 

## NOTE ==> if you have ros melodic installed on ubuntu 18.04 or ros kinetic installed on ubuntu 16.04 that will be good to build.

---

```bash
#clone the repository to your own machine
git clone https://github.com/khshmt/SFND_Lidar_Obstacle_Detection.git

#go to the repo directory
cd ./SFND_Lidar_Obstacle_Detection

#make a build directory and go to it
mkdir build && cd build

#refere to the CMake file
cmake ..

#build
make -j4
```

## The Project Output
### Clustering and box bounding for all the obstacles in the road.

![output of the build executable file](media/ObstacleDetectionFPS.gif)