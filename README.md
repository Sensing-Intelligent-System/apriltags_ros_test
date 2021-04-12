# apriltags_ros_test
ROS tutorials

1. apriltags
2. unittest

## How to run this class exercise

1. Create a Directory ~/sis2021_ws/src
2. Clone repo in ~/sis2021_ws/src https://github.com/Sensing-Intelligent-System/apriltags_ros
3. Fork [https://github.com/Sensing-Intelligent-System/apriltags_ros_test](https://github.com/Sensing-Intelligent-System/apriltags_ros_test) and clone it in ~/sis2021_ws/src
4. Modify the example.launch in ~/sis2021_ws/src/apriltags_ros_test/launch
5. If you finish this class exercise,please open a Pull Request(PR).

## Rosbag is a powerful tool for you to record and playback your simulation.

Download:[https://drive.google.com/file/d/16u-AsnN8Nm9cS6qzcpAeGx2fzADuKZCS/view?usp=sharing](https://drive.google.com/file/d/16u-AsnN8Nm9cS6qzcpAeGx2fzADuKZCS/view?usp=sharing)

*** To playback, type the following command in a terminal

rosbag play -l tag_36h11_id6.bag

*** This bag file contains two rostopic,camera_info and image_rect_color.

***The tag's tag_family is 36h11.***

***The tag's ID is 6.***

***The tag's size is 0.081.***
