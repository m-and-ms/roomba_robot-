# roomba_robot
This repository is for "SPC 428:Robotics and Mechatronics" Course project.

may-classify : is the classification package 

1-data is not present yet under development gazebo dataset

2-train-multiclass.py run if you wish to retarain multy class classification model 

3-predict-multiclass.py is for prediction 
- rosnode2 is node for running prediction on simulation 



Launch files :

roomba_robot_description : is for the for the robot description in simulation 

empty_world : for the robot indoor enviroment 

roomba_rtab: is for running rtab package (generates 3d maps for enviroment (SLAM))
roomba_gemaping : for running gemapping package (generates 2d maps for enviroment(SLAM) )

src/telop.py is for robot control with keyboard 

src/navigation.cpp : for robot control using navigation stack package (The Navigation Stack is fairly simple on a conceptual level. It takes in information from odometry and sensor streams and outputs velocity commands to send to a mobile base)


