# Astra_ptrack
===========

Astra_ptrack is an open source project launched in 2019 to create a scalable, multi-camera solution for person tracking that specifically aims to support applications in education, art, and culture.

With the advent of commercially available consumer depth sensors, and continued efforts in computer vision research to improve multi-modal image and point cloud processing, robust person tracking with the stability and responsiveness necessary to drive interactive applications is now possible at low cost.  But the results of such research are not easy to use for application developers. We believe that a disruptive project is needed to bridge these two worlds and enable artists and creators to work with real-time person tracking.   OpenPTrack aims to support “creative coders” in the arts, culture, and educational sectors who wish to experiment with real-time person tracking as an input for their applications.

The project contains numerous state-of-the-art algorithms for RGB and/or depth tracking, and has been created on top of a modular node based architecture, to support the addition and removal of different sensor streams online.

OpenPTrack is led by UCLA REMAP and Open Perception. Key collaborators include the University of Padova and Electroland. Code is available under a BSD license.  Portions of the work are supported by the National Science Foundation (IIS-1323767).
Note that the OpenPose library used in pose recognition does not allow commercial repackaging of OpenPTrack pose recognition capabilities; please contact the CMU OpenPose team for a license.


OpenPTrack是一个开放源代码项目，于2013年启动，旨在为人员跟踪创建可扩展的多摄像机解决方案，该解决方案专门旨在支持教育，艺术和文化领域的应用。

随着市场上可买到的消费者深度传感器的出现，以及计算机视觉研究的不断努力来改善多模式图像和点云处理，现在可以以低成本实现具有驱动交互应用程序所必需的稳定性和响应性的强大的人员跟踪。但是，这种研究的结果对于应用程序开发人员来说并不容易使用。我们认为，需要一个颠覆性的项目来弥合这两个世界，并使艺术家和创作者能够进行实时人员跟踪。 OpenPTrack旨在为艺术，文化和教育领域的“创意编码员”提供支持，他们希望尝试使用实时人员跟踪作为其应用程序的输入。

该项目包含大量用于RGB和/或深度跟踪的最新算法，并且已在基于模块化节点的体系结构之上创建，以支持在线添加和删除不同的传感器流。

OpenPTrack由UCLA REMAP和Open Perception领导。主要合作者包括帕多瓦大学和伊莱兰德大学。代码在BSD许可下可用。部分工作得到了美国国家科学基金会（IIS-1323767）的支持。
请注意，姿势识别中使用的OpenPose库不允许对OpenPTrack姿势识别功能进行商业包装。请与CMU OpenPose团队联系以获得许可证。
If you use this code, please cite:

[OpenPTrack v1]
M. Munaro, A. Horn, R. Illum, J. Burke and R. B. Rusu. OpenPTrack: People Tracking for Heterogeneous Networks of Color-Depth Cameras. In IAS-13 Workshop Proceedings: 1st Intl. Workshop on 3D Robot Perception with Point Cloud Library, pp. 235-247, Padova, Italy, 2014. 

M. Munaro and E. Menegatti. Fast RGB-D people tracking for service robots. Journal on Autonomous Robots, vol. 37(3), pp. 227-242, Springer, 2014. 

[PoseEstimation and PoseRecognition]
M. Carraro, M. Munaro, J. Burke and E. Menegatti. Real-time marker-less multi-person 3D pose estimation in RGB-Depth camera networks. arXiv preprint arXiv:1710.06235, 2017.

Z. Cao, T. Simon, S. E. Wei, and Y. Sheikh, 2016. Realtime multi-person 2d pose estimation using part affinity fields. arXiv preprint arXiv:1611.08050.

T. Simon, H. Joo, I. A. Matthews, and Y. Sheikh, 2017, July. Hand Keypoint Detection in Single Images Using Multiview Bootstrapping. In CVPR (Vol. 1, p. 2).

[ObjectTracking]
Y. Zhao, M. Carraro, M. Munaro and E. Menegatti, Fast Multiple Object Tracking in RGB-D Camera Networks, in Intelligent Robots and Systems (IROS), 2017 IEEE/RSJ International Conference on, IEEE, 2017.
