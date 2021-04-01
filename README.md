# Making ros docker image
*You should run this code on a **Jetson device** (Nano, TX, Xavier, etc.)*

dependencies: 
- CUDA 10.2
- Python 3.6
- Pytorch 1.7.0
- ROS(Melodic)
- Librealsense

Usage:

**building docker image**

    xavier $ source docker/build.sh

**How to run**

    xavier $ source xavier_docker_run.sh
    docker $ source environment.sh
    
**If you want to enter same container**

    xavier $ source xavier_docker_join.sh
    docker $ source environment.sh

