# 背景
为了解决gazebo模型加载不出来的问题，我们可以采取预先下载好所有可能用到的模型，然后快速启动

# 使用流程
### 下载
```sh
cd ~/.gazebo
git clone https://github.com/GoesM/gazebo_models.git models
rm -rf models/.git
```

### 验证
```sh
export TURTLEBOT3_MODEL=waffle
ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py
```
