
ROS2에 맞게 포팅해놨습니다.

# Clone

```bash
git clone git@github.com:Metafarmers/livox_ros_driver2.git
```

# install dependency

```bash
rosdep install --from-paths . -y
```

# build

```bash
colcon build --cmake-args -DCMAKE_BUILD_TYPE=Release
```