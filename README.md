# pedestrian_with_collision_gazebo
This is an environment using velodyne simulation with 4 pedestrians walking in different style

Using ros melodic and Gazebo 9
## Compile
cd catkin_ws/src
git clone https://github.com/SDUPiggy/pedestrian_with_collision_gazebo.git
cd ..
catkin_make


## Add plugin
sudo cp libActorCollisionsPlugin.so /usr/lib/x86_64-linux-gnu/gazebo-9/plugins/

## Run
source ./devel/setup.bash
roslaunch velodyne_description example.launch

## Result
![image](https://github.com/SDUPiggy/pedestrian_with_collision_gazebo/blob/main/1.jpg)
![image](https://github.com/SDUPiggy/pedestrian_with_collision_gazebo/blob/main/2.jpg)
## Reference
https://github.com/osrf/gazebo/tree/gazebo11/examples/plugins/actor_collisions

https://github.com/BruceChanJianLe/gazebo-actor

https://blog.csdn.net/tanjia6999/article/details/102629735

https://blog.csdn.net/allenhsu6/article/details/114068662

https://github.com/lmark1/velodyne_simulator
