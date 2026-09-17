для запуска симулятора данного модуля прописать в терминал.

ros2 launch ar_webots_fms_ros2 module5.launch.py


для запуска навигации ROS2 в терминале прописать

ros2 launch ar_nav_ros2 bringup_launch.py

команды запуска конфигов rviz2 

ros2 launch ar_webots_fms_ros2 rviz_rmc1.launch.py # Для RMC1

ros2 launch ar_webots_fms_ros2 rviz_rmc2.launch.py # Для RMC2

ros2 launch ar_nav_ros2 rviz.launch.py # Для Nav2


для запуска решения складского кейса гетерогенной группой прописать в терминал данную команду

python3 start.py
