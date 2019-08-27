# Dependency

- PCL 1.9.1.99

- OpenCV 3.3.1

-

# How to launch a code

- Install ros/intel_realsense, following these instructions https://github.com/IntelRealSense/realsense-ros

- Downloading these files in "catkin_ws/src"

- make "build" directory in "matching_algorithm"

- command in "build" directory, 'cmake -DCMAKE_BUILD_TYPE=Release ..'

- command in "build" directory, 'make'

- move "blocks" directory into "catkin_ws"

- make "output_cloud" directory in "matching_algorithm"

- command 'roslaunch realsense2_camera rs_camera.launch align_depth:=true'

- command in "catkin_ws" directory, 'rosrun matching_algorithm build/matching_algorithm'

# Notice

- You have to run this code in bright space

- You have to run this code in empty space except blocks
