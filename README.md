# futaba_robot
moveit! with 5-DOF robot arm

[千葉工業大学先進工学部 2019年度のロボットシステム学 課題2 -ROSで何か作る-](https://ryuichiueda.github.io/robosys2019/lesson14.html#/5)

## MoveIt!でGazebo上のマニピュレータを動かす.

[![](https://img.youtube.com/vi/2IKX3fjSp4U/0.jpg)](https://youtu.be/2IKX3fjSp4U)

https://youtu.be/2IKX3fjSp4U

マニピュレータのCADモデルは[takayan660](https://github.com/takayan660)さんの[5DOF](https://github.com/takayan660/RobotArm_Simulator/tree/master/5DOF/インポートされたコンポーネント/Assem1)を使わせていただいた．
(https://github.com/takayan660/RobotArm_Simulator/tree/master/5DOF/インポートされたコンポーネント/Assem1)

URDFの製作にあたり，[syuntoku14](https://github.com/syuntoku14)さんの[fusion2urdf](https://github.com/syuntoku14/fusion2urdf)を使わせていただいた．(https://github.com/syuntoku14/fusion2urdf)

[ryuichiueda](https://github.com/ryuichiueda)先生のROS講義のスライドの一部を参考にさせていただいた．(https://github.com/ryuichiueda/robosys2019)

## 環境
Ubuntu 16.04
ROS kinetic
MoveIt! rviz gazebo

## 実行方法

~/catkin_ws/src下にgit clone
catkin_make後，roslaunch futaba_robot/src/all.launch を実行
