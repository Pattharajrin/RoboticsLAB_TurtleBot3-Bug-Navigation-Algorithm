# RoboticsLAB_TurtleBot3-Bug-Navigation-Algorithm

โปรเจกต์นี้เป็นการพัฒนา อัลกอริธึม Bug สำหรับ TurtleBot3 หุ่นยนต์ที่ออกแบบมาเพื่อหาทางไปยังจุดหมายโดยหลบหลีกสิ่งกีดขวาง หุ่นยนต์จะใช้เซ็นเซอร์ LiDAR ในการตรวจจับสิ่งกีดขวาง และหลีกเลี่ยงสิ่งกีดขวางที่เจอ โดยเดินตามเส้นทางของสิ่งกีดขวางจนกว่าจะสามารถกลับเข้าสู่เส้นทางเดิมเพื่อไปยังเป้าหมาย

cd labrobo3_ws/

colcon build

source install/setup.bash

ros2 run my_bug0 bug0_navigator


export TURTLEBOT3_MODEL=burger

ros2 launch turtlebot3_gazebo empty_world.launch.py


export TURTLEBOT3_MODEL=burger

ros2 launch turtlebot3_bringup robot.launch.py

