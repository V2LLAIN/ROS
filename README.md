# ROS 과제

![image](https://github.com/V2LLAIN/ROS/assets/104286511/2fe41399-996b-4431-a91a-08c3ac972f7d)
    
### build 진행.
    colcon build --packages-select urdf_tutorial_r2d2   
#####
    source install/setup.bash 
        
### rviz2로 2개의 창에서 순서대로 실행.
    ros2 launch urdf_tutorial_r2d2 demo.launch.py 
#####
    rviz2 -d install/urdf_tutorial_r2d2/share/urdf_tutorial_r2d2/r2d2.rviz
