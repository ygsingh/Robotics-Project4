# Instructions to run project
## Terminal 1

'''
$ cd catkin_ws
$ catkin_make
$ source devel/setup.bash
$ roslaunch my_robot world.launch
'''

## Terminal 2

'''
$ cd catkin_ws
$ source devel/setup.bash
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
'''

## Terminal 3

'''
$ cd catkin_ws
$ source devel/setup.bash
$ rosrun my_robot mapping.launch 
'''
ctrl+C terminal 3: rtabmap.db is saved at /root/.ros/rtabmap.db

## Database Analysis
'''
$ rtabmap-databaseViewer ~/.ros/rtabmap.db
'''


