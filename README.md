# ROSBOT

本仓库建立目的是为了给同学们在ROS机器人开发中提供帮助。

国外仓库链接Github：https://github.com/Githubcxy666/ROSBOT

国内仓库链接Gitee：https://gitee.com/wybros/ROSBOT

仓库部分资料来源互联网，如有侵权，请联系邮箱 344214187@qq.com，必定在72小时内处理。

如果同学们有新资源提供分享，也请联系邮箱 344214187@qq.com。

关注微信公众号【ROS机器人开发】，获取更多ROS机器人开发资料，还有抽奖活动！

![扫码_搜索联合传播样式-标准色版2(1)](https://gitee.com/wybros/Image/raw/master/img/扫码_搜索联合传播样式-标准色版2(1).jpg)



## 目录

### [ROS安装](#1)

### [ROS开发环境搭建](#2)

### [ROS相关软件安装](#3)

### [ROS问题总汇](#4)

### [ROS教程](#5])

### [ROS进程功能教程](#6)

### [ROS代码demo](#7)

### [ROS常用命令](#8)

### [ROS文件详解](#9)

### [ROS人机界面开发教程](#10)

### [ROS安卓APP](#11)

### [ROS源码解读](#24)

### [ROS书籍推荐](#12)

### [Git使用教程](#13)

### [机器人运动学模型](#14)

### [路径规划算法](#15)

### [SLAM](#16)

### [机器视觉](#17)

### [语音识别和控制](#18)

### [人工智能](#23)

### [机器狗项目spotMicro](#19)

### [硬件资料](#20)

### [编程资料](#21)

### [机器人资料](#30)

### [贡献者](#22)

&nbsp;

&nbsp;



## <span id="1">ROS安装</span>

### 虚拟机ROS安装

- #### 虚拟机镜像安装教程（阿里云）

  - [ubuntu-16.04.7-desktop-amd64 镜像下载链接](http://mirrors.aliyun.com/ubuntu-releases/16.04/ubuntu-16.04.7-desktop-amd64.iso)
  - [ubuntu-18.04.5-desktop-amd64 镜像下载链接](http://mirrors.aliyun.com/ubuntu-releases/18.04/ubuntu-18.04.5-desktop-amd64.iso)
  - [ubuntu-20.04.2.0-desktop-amd64 镜像下载链接](http://mirrors.aliyun.com/ubuntu-releases/20.04/ubuntu-20.04.2.0-desktop-amd64.iso)
  
- #### [ROS rosdep init/update 百分百解决教程](https://mp.weixin.qq.com/s/mghnF4sesImHpg4ScZ-bRA)

- 
  #### 	    kinect版本安装教程

- #### 	    [melodic版本安装教程](https://mp.weixin.qq.com/s?__biz=MzU2OTMwNjE2MA==&mid=2247483712&idx=1&sn=8019b598e7e5ba40f270f43625cd66b7&chksm=fc81fc1fcbf67509ff9faba6730ca278a8f34840abe0a6e05fc6699453df0fc0912ad1c3c2c1&token=168864254&lang=zh_CN#rd)

- #### 	[notice版本安装教程（附带ros init失败解决办法）](http://www.autolabor.com.cn/book/ROSTutorials/chapter1/12-roskai-fa-gong-ju-an-zhuang/124-an-zhuang-ros.html)

&nbsp;

### 树莓派ROS安装

- #### 树莓派安装教程

- 
  #### 	kinect版本安装教程

- #### 	melodic版本安装教程

- #### 	notice版本安装

&nbsp;

### Jetson nano ROS安装

- #### Jetson nano 安装教程

- 
  #### 	kinect版本安装教程

- #### 	melodic版本安装教程

- #### 	notice版本安装

&nbsp;

## <span id="2">ROS开发环境搭建</span>

### Vscode安装和配置（C++和Python）

- #### [安装和配置教程](http://www.autolabor.com.cn/book/ROSTutorials/chapter1/14-ros-ji-cheng-kai-fa-huan-jing-da-jian/142-an-zhuang-vscode.html)

&nbsp;

### Clion安装和配置

- #### [安装教程](https://blog.csdn.net/ChuiGeDaQiQiu/article/details/114324796)

- #### [配置教程](https://www.jb51.net/article/193563.htm)

&nbsp;

## <span id="3">ROS相关软件安装和使用</span>

### cartographer

- #### [cartographer 一键安装](https://github.com/WLwind/cartographer_installation)

- #### cartographer使用

  - ##### [创客智造教程](https://www.ncnynl.com/archives/201810/2775.html)

  - ##### [ROS(Kinetic和Melodic)下使用cartographer踩坑记录和部分谣言终结](https://blog.csdn.net/weixin_41349117/article/details/100551517)

  - ##### [google-cartographer机器人SLAM建图](https://www.cnblogs.com/hiram-zhang/p/10415865.html)

&nbsp;

### teb_local_planner

- #### [安装](https://blog.csdn.net/xiekaikaibing/article/details/80197164?utm_medium=distribute.pc_relevant.none-task-blog-baidujs-1)

- #### [使用](https://blog.csdn.net/xiekaikaibing/article/details/80197164)

- #### [调参](https://blog.csdn.net/Fourier_Legend/article/details/89398485)

&nbsp;

### ROS serial 串口通信功能包安装


  - 
    #### 	Kinect版本安装

    `sudo apt-get install ros-kinetic-serial`

  - #### 	melodic版本安装

    `sudo apt-get install ros-melodic-serial`

  - #### 	notice版本安装

    `sudo apt-get install ros-notice-serial`

- #### ROS serial 使用

&nbsp;

### 串口调试软件安装

建议使用cutecom


  - #### [cutecom 安装和使用教程](https://blog.csdn.net/shui1025701856/article/details/79277484/)

  - #### [minicom 安装和使用教程](https://blog.csdn.net/mybelief321/article/details/8987502)

&nbsp;

### opencv安装

`pip install opencv-python`

&nbsp;

### 键盘控制功能包安装

#### [teleop_twist_keyboard 安装](https://github.com/ros-teleop/teleop_twist_keyboard)

&nbsp;

### ROS gazebo仿真模型


  gazebo模型官方下载链接：https://github.com/osrf/gazebo_models

  为了方便大家下载，已上传到百度云盘

  关注微信公众号：ROS机器人开发

  回复  999 即可获取下载链接

&nbsp;

### navigation功能包安装

- 
  #### 	Kinect版本安装教程

  `git clone -b kinetic-devel https://github.com/ros-planning/navigation.git`

- #### 	melodic版本安装教程

  `git clone -b melodic-devel https://github.com/ros-planning/navigation.git`

- #### 	notice版本安装

  `git clone -b noetic-devel https://github.com/ros-planning/navigation.git`

&nbsp;

### robot_pose_ekf 安装教程

`git clone https://github.com/ros-planning/robot_pose_ekf.git`

使用

[使用robot_pose_ekf对传感器信息融合](http://www.mamicode.com/info-detail-2140777.html)

&nbsp;

### 雷达驱动包安装

- 
  #### 	RPLIDAR(思岚)

  官方Github链接：https://github.com/Slamtec/rplidar_ros

  `git clone https://github.com/Slamtec/rplidar_ros.git`

  RPLidar A1示意图
  
  ![请输入图片描述](https://gitee.com/wybros/Image/raw/master/img/rplidar_A1.png)
  
  
  
  RPLidar A2示意图
  
  ![请输入图片描述](https://gitee.com/wybros/Image/raw/master/img/rplidar_A2.png)

&nbsp;

## [<span id="4">ROS问题总汇</span>](problems.md)

&nbsp;

## <span id="5">ROS教程</span>

**以下排名不分先后**

### 	ROS WIKI 

#### [网站链接](http://wiki.ros.org/cn/ROS/Tutorials)

&nbsp;

### 	古月居

- 
  #### 		ROS入门21讲

  ##### [视频教程](https://www.bilibili.com/video/BV1zt411G7Vn)

- #### ROS机器人开发案例

  ##### [视频教程](https://www.bilibili.com/video/BV1vb41177qN)

- #### 		ROS机械臂开发原理

  ##### [视频教程](https://www.bilibili.com/video/BV14b411p7Hm)

&nbsp;

### 	中国大学MOOC --《机器人操作系统入门》

#### [视频教程](https://www.bilibili.com/video/BV1PJ411D7mj?from=search&seid=367619698396859163)

#### [课程讲义---Gitbook](https://sychaichangkun.gitbooks.io/ros-tutorial-icourse163/content/ )

#### [代码示例---Github](https://github.com/DroidAITech/ROS-Academy-for-Beginners )（注意版本）

&nbsp;

### 奥特学园 -- ROS机器人入门课程《ROS理论与实践》零基础教程


作者：赵虚左老师

#### [视频教程](https://www.bilibili.com/video/BV1Ci4y1L7ZZ?p=1)

#### [课程文档]( http://www.autolabor.com.cn/book/ROSTutorials/)

&nbsp;

### ROS小课堂 -- ROS快速入门课程

#### [视频教程](https://space.bilibili.com/407185400/channel/detail?cid=147661)

&nbsp;

### ROS入门教程 - 创客智造

#### [网站链接](https://www.ncnynl.com/archives/201608/496.html)

&nbsp;

### 深蓝学院 

- #### ROS机器人开发案例——浅谈如何将ROS应用于机器人开发

  ##### [视频教程](https://www.bilibili.com/video/BV1Yb411h7jg)

&nbsp;

### 黑马程序员_零基础玩转机器人操作系统ROS

#### [视频教程](https://www.bilibili.com/video/BV1Bh411y7QM)

&nbsp;

### 小白学移动机器人

#### [课程文档](https://blog.csdn.net/zhao_ke_xue/article/details/108138981)

&nbsp;

### 小虎哥哥爱学习

#### [课程文档](https://www.cnblogs.com/hiram-zhang/p/10802569.html)

&nbsp;

## <span id="6">ROS进阶教程</span>

### 多点导航

&nbsp;

### ROS开机启动

- #### [robot_upstart方法](https://zhuanlan.zhihu.com/p/163048849)

- #### [ubuntu自带upstart方法](https://blog.csdn.net/r1141207831/article/details/102941613)

&nbsp;

### 虚拟墙

- #### [虚拟墙使用教程](https://blog.csdn.net/weixin_42005898/article/details/101757709)

### 语音交互

- #### [语音交互](#18)

### 使用自定义的全局路径规划算法

- #### [ROS WIKI教程](http://wiki.ros.org/navigation/Tutorials/Writing%20A%20Global%20Path%20Planner%20As%20Plugin%20in%20ROS)

- #### [创客智造教程](https://www.ncnynl.com/archives/201708/1887.html)

&nbsp;

### 多车仿真

&nbsp;

### 搭建ROS仿真小车模型

- #### [ROS WIKI URDF 教程](http://wiki.ros.org/cn/urdf)

- #### [ROS探索总结（二十三）——解读URDF](https://www.guyuehome.com/372)

- #### [ROS机器人建模与仿真(一)--URDF机器人建模](https://blog.csdn.net/weixin_43619346/article/details/107917683)

&nbsp;

### 相机模拟激光数据并避障

- #### [相机模拟激光数据并避障教程](https://blog.csdn.net/qq_39266065/article/details/108714973)

&nbsp;

### 目标检测

- #### [实时目标检测(darknet_ros)](https://www.rt-thread.org/document/site/tutorial/smart-car/object-detection/object-detection/)

- #### [Ros平台下基于face_recognition的人脸检测及识别](https://blog.csdn.net/qq_41658212/article/details/105399909)

- #### [摄像头标定和opencv识别](https://zhuanlan.zhihu.com/p/179166753)

&nbsp;

## <span id="7">ROS代码demo</span>

### Topic通信

- #### C++版本

- #### Python版本

### 自义定msg

- #### C++版本

- #### Python版本

### Server通信

- #### C++版本

- #### Python版本

### 参数服务器

- #### C++版本

- #### Python版本

&nbsp;

## <span id="8">ROS常用命令</span>

#### [ROS常用命令详解](http://www.autolabor.com.cn/book/ROSTutorials/di-2-zhang-ros-jia-gou-she-ji/24-chang-yong-ming-ling.html)

&nbsp;

## <span id="9">ROS文件详解</span>

### [launch 文件详解](http://www.autolabor.com.cn/book/ROSTutorials/5/45-rosjie-dianguan-li-launch-wen-jian.html)

### [CMakeLists.txt 文件详解](https://blog.csdn.net/weixin_42587961/article/details/86381730)

### [package.xml 文件详解](https://blog.csdn.net/qq_43667745/article/details/90137505)

&nbsp;

## <span id="10">ROS人机界面开发教程</span>

### [基于Qt5的ROS人机交互界面(蒋程扬老师)](https://github.com/chengyangkj/Ros_Qt5_Gui_App)

![](https://gitee.com/wybros/Image/raw/master/img/人机界面演示001(1).jpg)

&nbsp;





## <span id="24">ROS源码解读</span>

### [base_control功能包代码解析    视频](https://www.bilibili.com/video/BV19i4y1w7FQ?p=1)

### [robot_vision功能包代码解析    视频](https://www.bilibili.com/video/BV19i4y1w7FQ?p=2)

### [lidar文件夹和robot_navigation功能包代码解析    视频](https://www.bilibili.com/video/BV19i4y1w7FQ?p=3)

### [robot_simulation功能包代码解析    视频](https://www.bilibili.com/video/BV19i4y1w7FQ?p=4)

### [ROS Navigation之move_base完全详解  文章](https://haoqchen.site/2018/11/27/move-base-code/)

### [ROS Navigation包的理解    文章](https://blog.csdn.net/qq91752728/article/details/79863677)

### [ROS基础教程--CostMap_2D包的一些理解  文章](https://blog.csdn.net/jinking01/article/details/79455962)

### [Costmap2D代价地图源码解读-静态层StaticLayer  文章](https://blog.csdn.net/Neo11111/article/details/104849757)

### [Costmap2D代价地图源码解读-障碍层ObstacleLayer  文章](https://blog.csdn.net/Neo11111/article/details/104852657/)

### [Costmap2D代价地图源码解读-膨胀层InflationLayer  文章](https://blog.csdn.net/Neo11111/article/details/104869048)

### [Recovery Behavior恢复行为源码解读](https://blog.csdn.net/Neo11111/article/details/104884063)





&nbsp;

## <span id="11">ROS安卓APP</span>

&nbsp;

## [<span id="12">ROS书籍推荐</span>](books.md)

&nbsp;

## <span id="13">Git使用教程</span>

### [高质量的Git中文教程](https://github.com/geeeeeeeeek/git-recipes)

### [Git小白教程](https://rogerdudler.github.io/git-guide/index.zh.html)

### [Git的奇技淫巧](https://github.com/521xueweihan/git-tips)

&nbsp;


## <span id="14">机器人运动学模型</span>

### 两轮差速结构

### [两轮差速运动学模型详解](https://blog.csdn.net/iProphet/article/details/83661753)

<img src="https://gitee.com/wybros/Image/raw/master/img/v2-783b667ae182b0847d49e2f664c83993_1440w.jpg" alt="img" style="zoom:50%;" />

&nbsp;

### 麦克纳姆结构

### [麦克纳姆运动学模型详解](https://blog.csdn.net/weixin_30627381/article/details/97069120)

<img src="https://gitee.com/wybros/Image/raw/master/img/1583484317375227.png" alt="微信图片_20200306105948.png" style="zoom:67%;" />

&nbsp;

### 阿克曼转向结构

### [阿克曼转向运动学模型详解](https://blog.csdn.net/u013914471/article/details/82968608)

<img src="https://gitee.com/wybros/Image/raw/master/img/1620454828(1).jpg" alt="1620454828(1)" style="zoom:50%;" />

&nbsp;


## <span id="15">路径规划算法</span>

### 基于图搜索的路径规划算法

- #### Dijkstra算法（D）

  <img src="https://gitee.com/wybros/Image/raw/master/img/下载 (1).gif" alt="下载 (1)" style="zoom:60%;" />

  - ##### 文章

    - [Dijkstra算法原理](https://blog.csdn.net/yalishadaa/article/details/55827681)
  
  - ##### 视频
  
    - [《Dijkstra算法讲解》（IR艾若机器人）](https://www.bilibili.com/video/BV1yT4y1T7Eb?p=2)
    - [《路径规划与轨迹跟踪系列算法学习第1讲Dijkstra算法》by 小黎的Ally](https://www.bilibili.com/video/BV19T4y1M7uR)

&nbsp;

- #### A星算法（A* /Astar）

  <img src="https://gitee.com/wybros/Image/raw/master/img/下载.gif" alt="下载" style="zoom:60%;" />

  

  - ##### 文章
  
    - [A*算法详解 一看就会 手把手推导 完整代码注释](https://mp.weixin.qq.com/s?__biz=MzU2OTMwNjE2MA==&mid=2247485317&idx=1&sn=4408d8f55a4f99544e3160982de1a3a3&chksm=fc81fadacbf673cc4c603d90174fe7b8561d8970b8c3b60a67516c1d4bb29dc06382bdbc4cb1&token=168864254&lang=zh_CN#rd)
  
  - ##### 视频
  
    - [《A*算法讲解》by IR艾若机器人](https://www.bilibili.com/video/BV1yT4y1T7Eb?p=4)
    - [《路径规划与轨迹跟踪系列算法学习第4讲A*算法》by 小黎的Ally](https://www.bilibili.com/video/BV1Jt4y1z7Ry)

&nbsp;

- #### D星算法（D* / Dynamic A）

  <img src="https://gitee.com/wybros/Image/raw/master/img/D星.gif" alt="D星" style="zoom:60%;" />
  
  - 文章
    - [D*算法详解 一看就会 手把手推导 完整代码注释](https://mp.weixin.qq.com/s?__biz=MzU2OTMwNjE2MA==&mid=2247485939&idx=1&sn=9a28d04edd52d0fdd1f30a860d8bead3&chksm=fc81f4accbf67dbabbf1ad5c8f944d7f35fff6999ab9cf35d1db21760282f41d2d254e9bfcfd&token=168864254&lang=zh_CN#rd)
  - 视频

### 基于采样的路径规划算法

- #### RRT算法

  <img src="https://gitee.com/wybros/Image/raw/master/img/RRT.gif" alt="RRT" style="zoom:60%;" />

  - ##### 文章

    - [RRT算法详解 一看就会 手把手推导 完整代码注释](https://mp.weixin.qq.com/s?__biz=MzU2OTMwNjE2MA==&mid=2247486008&idx=1&sn=81529e2ac1cb365852a8cfa59150ac4c&chksm=fc81f767cbf67e71419c285052213ad2638d333180492d8475ed3e8716bd03ebdaa452cffbf5&token=168864254&lang=zh_CN#rd)

  - ##### 视频

    - [《RRT算法讲解》（IR艾若机器人）](https://www.bilibili.com/video/BV1yT4y1T7Eb?p=5)

- #### RRT*算法
  - ##### 文章

    - [【规划】RRT*算法图解](https://blog.csdn.net/yuxuan20062007/article/details/88843690)

  - ##### 视频

    - [《RRT*算法讲解》（IR艾若机器人）](https://www.bilibili.com/video/BV1yT4y1T7Eb?p=6)
  
- #### Informed RRT*算法

<img src="https://gitee.com/wybros/Image/raw/master/img/INFORMEDRTRTXING.gif" style="zoom:60%;" />

  - ##### 文章
  
    - [Informed RRT*论文](https://arxiv.org/pdf/1404.2334v2.pdf) 
    - [informed RRT*简述](https://zhuanlan.zhihu.com/p/162948527)
    
  - ##### 视频
  
    - [《Informed RRT* 算法讲解》（IR艾若机器人）](https://www.bilibili.com/video/BV1yT4y1T7Eb?p=7)

&nbsp;

### 全覆盖路径规划算法

- #### [full_coverage_path_planner](https://github.com/nobleo/full_coverage_path_planner)

<img src="https://github.com/nobleo/full_coverage_path_planner/raw/master/doc/fcpp_robot_0_5m_plus_tool_0_2m.png" alt="BSA" style="zoom:50%;" />



- #### [BoustrophedonCellularDecompositionPathPlanning](https://github.com/RicheyHuang/BoustrophedonCellularDecompositionPathPlanning)

<img src="https://gitee.com/wybros/Image/raw/master/img/BCDPP1.gif" style="zoom:50%;" />

- #### [CoveragePathPlanning](https://github.com/18alantom/CoveragePathPlanning)

![ShapefileOverlay](https://github.com/18alantom/CoveragePathPlanning/raw/master/demo_media/kmstcsh.png)

&nbsp;

## <span id="16">SLAM</span>

### 激光slam

- #### 文章

- #### 视频

  - [《slam 激光传感器与无人驾驶（完）》](https://www.bilibili.com/video/BV1hb411L7VF?from=search&seid=428409986740182790)

### 视觉slam

- #### 文章

  - ##### [《视觉SLAM十四讲》笔记摘抄](https://blog.csdn.net/ncepu_Chen/article/details/105322585)

- #### 视频

  - [《视觉十四讲（第二版）》（高翔老师）](https://www.bilibili.com/video/BV1Dz4y1S7gn?p=1)
  - [《浙江大学视觉slam公开课-从视频标定到SLAM》](https://www.bilibili.com/video/BV1ax411R7Hd?p=1)

&nbsp;


## <span id="17">机器视觉</span>

### ROS与机器视觉教程 - 创客智造

#### [教程链接](https://www.ncnynl.com/archives/201610/934.html)

### 计算机视觉（本科） 北京邮电大学 鲁鹏 清晰完整合集

#### [视频链接](https://www.bilibili.com/video/BV1nz4y197Qv)

### OpenCV计算机视觉实战(Python版)

#### [视频链接](https://www.bilibili.com/video/BV1ct411F7Te?from=search&seid=17839174235953044601)

### 计算机视觉零基础入门

#### [视频链接](https://www.bilibili.com/video/BV19x411X7k6?from=search&seid=17839174235953044601)

&nbsp;

## <span id="18">语音识别和控制</span>

### ROS与语音交互教程 - 创客智造

#### [教程链接](https://www.ncnynl.com/category/ros-voice/)

### 古月居 ROS探索总结（十）—— 语音控制

#### [教程链接](https://www.guyuehome.com/260)

### 天之博特  中文ROS语音交互模块

#### [教程链接](http://doc.tianbot.com/rosecho/1586400)

### ROS小课堂 

#### [视频链接](https://www.youku.com/profile/index/?spm=a2hbt.13141534.1_1.1&uid=UMTUzNzkwNTA1Ng==)（搜索语音交互）

![ROS小课堂-语音交互截图](https://gitee.com/wybros/Image/raw/master/img/ROS小课堂-语音交互截图.png)

### 小虎哥哥爱学习

#### [课程链接](https://www.cnblogs.com/hiram-zhang/p/10421162.html)

&nbsp;

## <span id="23">人工智能</span>

### 李宏毅2020机器学习深度学习(完整版)国语

#### [视频教程](https://www.bilibili.com/video/BV1JE411g7XF)

### 《PyTorch深度学习实践》完结合集

#### [视频教程](https://www.bilibili.com/video/BV1Y7411d7Ys)

### 李宏毅2021春机器学习课程

#### [视频教程](https://www.bilibili.com/video/BV1Wv411h7kN)

### [中英字幕]吴恩达机器学习系列课程

#### [视频教程](https://www.bilibili.com/video/BV164411b7dx)













&nbsp;

## [<span id="19">机器狗项目spotMicro</span>](https://github.com/mike4192/spotMicro)

<img src="https://gitee.com/wybros/Image/raw/master/img/SpotMicroAI_complete_1.jpg" alt="SpotMicroAI" style="zoom:50%;" />



&nbsp;

## ROS资料

《ROS 导航功能调优指南》       [百度链接](https://pan.baidu.com/s/1jotYxTdUu3IX1AEx_1itrg)→提取码：a70m&emsp;&emsp;&emsp; [城通网盘](https://089m.com/f/7753041-495669076-1fe528)→提取码：5385

《launch文件整理》       [百度链接](https://pan.baidu.com/s/15_V-Kb0hreOv1JWKM_Z6Dg)→提取码：y9rz&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669066-559831)→提取码：5385

《ROS机器人编程实践 by Morgan Quigley》       [百度链接](https://pan.baidu.com/s/1Ey1LoSstQ3t6xTKcM8GBSw)→提取码：d6fw&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669131-e919f3)→提取码：5385

《ROS机器人程序设计》       [百度链接](https://pan.baidu.com/s/1COnXjeNjE8E3SGHo8b9wZA)→提取码：7rpr&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669162-a3f923)→提取码：5385

《ROS机器人高效编程（原书第3版）高清可编辑》       [百度链接](https://pan.baidu.com/s/1atMR20JeKnM4-2Ts71_Hhg)→提取码：0iov&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669202-1f1d37)→提取码：5385

《ROS机器人开发实践》       [百度链接](https://pan.baidu.com/s/1dOUpULuhln9Ox3-jV1qRjQ)→提取码：spl2&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669227-03d6f3)→提取码：5385

《ROS进阶实例》       [百度链接](https://pan.baidu.com/s/1Mfy7386r6fuVvOgO8A1q9g)→提取码：s7b4&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669267-dd71fc)→提取码：5385

《掌握ROS机器人编程》       [百度链接](https://pan.baidu.com/s/1t20R0CxbucI176ffnZ7s3A)→提取码：sghq&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669283-a93307)→提取码：5385

《ROSWIKI官网学习资料》       [百度链接](https://pan.baidu.com/s/1BOkGGltau419-B43BGUIyw)→提取码：7i0r&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669082-985c19)→提取码：5385

&nbsp;

## <span id="20">硬件资料</span>

### 底层控制板

- #### STM32

- #### arduino

### 上层控制板


- #### 树莓派

- #### jetson nano

### 传感器

- #### IMU

  - [《第三讲 AHRS姿态解算》](https://blog.csdn.net/superfly_csu/article/details/79128460)
  - [《三分钟了解惯性导航系统、加速度计、陀螺仪的工作原理》](http://www.elecfans.com/emc_emi/639253.html)
  - [《IMU原理及姿态融合算法详解》](https://blog.csdn.net/RoboChengzi/article/details/97616482)

- #### 里程计

- #### 摄像头





&nbsp;

## <span id="21">编程资料</span>

### C/C++

- #### 电子书

  - 《21天学通c++_第7版》       [百度链接](https://pan.baidu.com/s/1hKlncWmAM_1f4S6ijb-t-w)→提取码：4lpg&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495668812-40fd4d)→提取码：5385
  - 《C++ Primer Plus（第6版）中文版》       [百度链接](https://pan.baidu.com/s/10VfkmYC6WsdmILWWZsDmSw)→提取码：5yiy&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495668975-be8826)→提取码：5385

- #### 视频教程

  - [黑马程序员C++从0到1入门编程（附C++编程环境搭建教程）](https://www.bilibili.com/video/BV1gb411Y7Yh)

### Python

- #### 电子书

  - 《Python编程  从入门到实践》       [百度链接](https://pan.baidu.com/s/1Qmn4ZNYWDu_ELIjw8C3b1w)→提取码：8vl8&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669022-641a32)→提取码：5385
  - 《Python3.5从零开始学》       [百度链接](https://pan.baidu.com/s/1gUJLCmWys0m5OY9Y08u68Q)→提取码：idit&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669061-afc504)→提取码：5385
  - 《byte-of-python-chinese-edition》       [百度链接](https://pan.baidu.com/s/1NbYNeNS5Ep9i22NlORUwdg)→提取码：1hyd&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669014-61fbcd)→提取码：5385

- #### 视频教程

  - [黑马程序员Python小白基础入门教程 Python入门到精通教程](https://www.bilibili.com/video/BV1Az4y1S7oK?p=1)

### Linux

- #### 电子书

  - 《鸟哥的Linux私房菜-基础篇-第四版》       [百度链接](https://pan.baidu.com/s/1k3y2yZwMXleHPB5hIYOqww)→提取码：t4dj&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669010-a05bb7)→提取码：5385

- #### 视频教程

  - [黑马程序员linux入门到精通 （上）](https://www.bilibili.com/video/BV1nW411L7xm)
  - [黑马程序员linux入门到精通 （下）](https://www.bilibili.com/video/BV1DW411G7VB)

&nbsp;



## <span id="30">机器人资料</span>

《规划算法》       [百度链接](https://pan.baidu.com/s/1wVHgzovGK1HoBVeBMgvr4w)       提取码：7s1h&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669430-5a5862)→提取码：5385

《概率机器人》       [百度链接](https://pan.baidu.com/s/1lYLBLZp-GIcoCyREYdDj6g)       提取码：89gd&emsp;&emsp;&emsp;[城通网盘](https://089m.com/f/7753041-495669332-71e4e3)→提取码：5385





&nbsp;

## <span id="22">扩展视频</span>



&nbsp;

## <span id="22">贡献者</span>

这个项目的存在要感谢所有贡献者。 请给我们一个 🌟 Star 🌟支持我们。 谢谢。 并感谢所有支持者！ 🙏