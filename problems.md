## ROS开发问题汇总

请使用 Ctrl + F 进行搜索

https://www.jianshu.com/p/b52d3a71cbf3

ROS init 

## 安装

Q1:

```shell
E: 无法获得锁 /var/lib/dpkg/lock - open (11: 资源暂时不可用)
E: 无法锁定管理目录(/var/lib/dpkg/)，是否有其他进程正占用它？
```

A1:

```
sudo rm /var/cache/apt/archives/lock  
sudo rm /var/lib/dpkg/lock
```

&nbsp; 

Q2:

```
sudo rosdep：找不到命令提示
```

A2:

```
sudo apt install python-rosdep
```

&nbsp;

Q3:

```
ERROR: cannot download default sources list from:
```

A3:

```

```

&nbsp;



### [ROS主从机配置教程](https://blog.csdn.net/weixin_43707303/article/details/86496335)

## 导航

### [ROS障碍层的无法清除干净的处理办法](https://blog.csdn.net/Bobsweetie/article/details/70194416?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.channel_param&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.channel_param)

### [costmap_2d: obstacle_layer中关于激光雷达障碍物清除不干净的解决](https://blog.csdn.net/xinmei4275/article/details/88760505)

### [ROS  costmap_2d局部障碍物无法清除和机器人到点摇摆](https://www.cnblogs.com/flyinggod/p/13463622.html)



