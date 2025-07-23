# Rust ROS2数据流

>地址：./examples/rust-ros2-dataflow
>
>关键词：ROS2，Rust

## 准备相关依赖
由于例子与`turtlesim`和`AddTwoInts`相关
```bash
$ sudo apt install ros-jazzy-turtlesim ros-jazzy-examples-rclcpp-minimal-service
```

## 构建
```bash
$ source /opt/ros/jazzy/setup.bash # 需要先应用ros2相关环境，在构建时才能找到相应ros消息类型
$ dora build dataflow.yml
```

## 启动
### 启动turtlesim
```bash
$ source /opt/ros/jazzy/setup.bash
$ ros2 run turtlesim turtlesim_node
```
### 启动AddTwoInts服务
```bash
$ source /opt/ros/jazzy/setup.bash
$ ros2 run examples_rclcpp_minimal_service service_main
```

```bash
$ source /opt/ros/jazzy/setup.bash
$ dora run dataflow.yml
```
