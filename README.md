# ROS 과제
![image](https://github.com/V2LLAIN/ROS/assets/104286511/76ec9923-2078-49ed-b112-437f7d2265db)
https://drive.google.com/drive/folders/1GjBSvA05GXC9IpCIbVNyZZK2JKpy41aj?usp=drive_link

### workspace 와 src 생성
    cd ~    
    mkdir -p dev_ws/src

### github에서 파일을 받은 이후 dependencies install 진행.
    cd ~/dev_ws/src    
    rosdep update    
    rosdep install --from-paths . --ignore-src --rosdistro $ROS_DISTRO -y
    
### xarm_ros2 build 진행.
    cd ~/dev_ws/    
    colcon build
        
### rviz2로 실행.
    cd ~/dev_ws/    
    source install/setup.bash
    ros2 launch xarm_description xarm6_rviz_display.launch.py
