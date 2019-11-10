Anomaly Detection Learning Resources
====================================

.. image:: https://img.shields.io/github/stars/yzhao062/anomaly-detection-resources.svg
   :target: https://github.com/yzhao062/anomaly-detection-resources/stargazers
   :alt: GitHub stars


.. image:: https://img.shields.io/github/forks/yzhao062/anomaly-detection-resources.svg?color=blue
   :target: https://github.com/yzhao062/anomaly-detection-resources/network
   :alt: GitHub forks


.. image:: https://img.shields.io/github/license/yzhao062/anomaly-detection-resources.svg?color=blue
   :target: https://github.com/yzhao062/anomaly-detection-resources/blob/master/LICENSE
   :alt: License


.. image:: https://awesome.re/badge-flat2.svg
   :target: https://awesome.re/badge-flat2.svg
   :alt: Awesome


----

`2D-3D matching <https://en.wikipedia.org/wiki/Anomaly_detection>`_
 is an exciting yet challenging field, which aims to build the connection between 2D image pixels to 3D point clouds.
 It is the foundation for camera localization, image to pint cloud fusion and virtual reality. 

This repository collects:


#. Books & Academic Papers 
#. Online Courses and Videos
#. Outlier Datasets
#. Open-source and Commercial Libraries/Toolkits
#. Key Conferences & Journals


**More items will be added to the repository**.
Please feel free to suggest other key resources by opening an issue report,
submitting a pull request, or dropping me an email @Huai Yu (huaiy@andrew.cmu.edu).
Enjoy reading!

----

Table of Contents
-----------------


* `1. Books & Tutorials <#1-books--tutorials>`_

  * `1.1. Books <#11-books>`_
  * `1.2. Tutorials <#12-tutorials>`_

* `2. Courses/Seminars/Videos <#2-coursesseminarsvideos>`_
* `3. Toolbox & Datasets <#3-toolbox--datasets>`_

  * `3.1. General toolbox: <#31-general-toolbox>`_
  * `3.2. Datasets <#32-datasets>`_

* `4. Papers <#4-papers>`_

  * `4.1. Overview & Survey Papers <#41-overview--survey-papers>`_
  * `4.2. Geometric 2D-3D features matching <#42-feature-matching>`_
  * `4.3. Simultaneously camera pose estimation and 2D-3D correspondence estimation <#43-Simultaneously-localization-and-matching>`_
  * `4.4. Airborne (UAV) image to terriseal LiDAr scanner point cloud matching <#44-airborne-LiDAR-matching>`_

* `5. Key Conferences/Workshops/Journals <#5-key-conferencesworkshopsjournals>`_

  * `5.1. Conferences & Workshops <#51-conferences--workshops>`_
  * `5.2. Journals <#52-journals>`_


----

1. Books & Tutorials
--------------------

1.1. Books
^^^^^^^^^^

`Multiple view geometry in computer vision <https://www.robots.ox.ac.uk/~vgg/hzbook/>`_ 
by Richard Hartley and Andrew Zisserman, 2004: Mathematic and geometric basis for 2D-2D and 2D-3D registration. 
A **must-read** for people in the field of registration. `[E-book] <http://cvrs.whu.edu.cn/downloads/ebooks/Multiple%20View%20Geometry%20in%20Computer%20Vision%20(Second%20Edition).pdf>`_

`Computer Vision: A Modern Approach <https://www.springer.com/gp/book/9783319547640>`_ 
by Charu Aggarwal and Saket Sathe: Great intro book for ensemble learning in outlier analysis.

`Algebra, Topology, Differential Calculus, and Optimization Theory For Computer Science and Engineering <https://www.cis.upenn.edu/~jean/gbooks/geomath.html>`_ By **Jean Gallier and Jocelyn Quaintance**. The latest book from upenn about the algebra and optimization theory.

`视觉SLAM十四讲 <https://github.com/gaoxiang12/slambook>`_ 高翔 and 张涛, et. al. 视觉陪准方向较易懂的入门教材。通俗讲述视觉匹配的物理模型， 数学几何基础，优化过程等。 新手必读。`[github] <https://github.com/gaoxiang12/slambook>`_ `[Videos] <https://space.bilibili.com/38737757>`_

`Three-Dimensional Computer vision-A Geometric Viewpoint <https://mitpress.mit.edu/books/three-dimensional-computer-vision>`_  Classical 3D computer vision textbook.

`An invitation to 3D vision <https://www.eecis.udel.edu/~cer/arv/readings/old_mkss.pdf>`_ a self-contained introduction to the geometry of three-dimensional (3- D) vision.

1.2. Tutorials
^^^^^^^^^^^^^^

=====================================================   ============================================  =====  ==========================================================================================================================================================================
Tutorial Title                                          Venue                                         Year   Materials
=====================================================   ============================================  =====  ==========================================================================================================================================================================
Long-Term Visual Localization under Changing            CVPR                                          2019   `[URL] <https://sites.google.com/view/ltvl2019/home>`_
Image Matching: Local Features & Beyond                 CVPR                                          2019   `[URL ] <https://image-matching-workshop.github.io/>`_
=====================================================   ============================================  =====  ==========================================================================================================================================================================

----

2. Courses/Seminars/Videos
--------------------------

**16-822: Geometry-based Methods in Vision**\ :
`[Website] <http://www.cs.cmu.edu/~hebert/geom.html>`_

**Talk: 2017以来的2D to 3D， 吴毅红， VALSE 2018**\ :
`[Into] <https://zhuanlan.zhihu.com/p/38611920>`_

----

3. Toolbox & Datasets
---------------------

3.1. General toolbox
^^^^^^^^^^^^^^^^^^^^^^

[**C++** and **Python**] `OpenCV <https://opencv.org/>`_\ : OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products.  

[**C++**] `PCL: Point Cloud Library <http://pointclouds.org/>`_. The Point Cloud Library (PCL) is a standalone, large scale, open project for 2D/3D image and point cloud processing.

[**C++**] `Ceres Solver <http://ceres-solver.org/index.html>`_\ :
Ceres Solver is an open source C++ library for modeling and solving large, complicated optimization problems. It can be used to solve Non-linear Least Squares problems with bounds constraints and general unconstrained optimization problems.

[**C++**] `Open3D <http://www.open3d.org/>`_\ : Open3D is an open-source library that supports rapid development of software that deals with 3D data. The Open3D frontend exposes a set of carefully selected data structures and algorithms in both C++ and Python. The backend is highly optimized and is set up for parallelization.


3.2. Datasets
^^^^^^^^^^^^^

**Indoor LiDAR-RGBD Scan Dataset**\ : http://redwood-data.org/indoor_lidar_rgbd/index.html

**ETH3D SLAM & Stereo Benchmarks**\ : https://www.eth3d.net/

**EuRoC MAV Dataset**\ : https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets

**ViViD : Vision for Visibility Dataset**\ : https://sites.google.com/view/dgbicra2019-vivid>

**Apolloscape: Scene Parsing**\ : http://apolloscape.auto/scene.html

**KITTI Visual Odometry dataset**\ : http://www.cvlibs.net/datasets/kitti/eval_odometry.php

**NCLT Dataset**\: http://robots.engin.umich.edu/nclt/

**Oxford Robotcar Dataset**\: https://robotcar-dataset.robots.ox.ac.uk/

----

4. Papers
---------

4.1. Overview & Survey Papers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
自定位技术在自动驾驶中的应用                                                                       中国计算机学会通讯             2018     [#hongdong2018]_                  No
A survey on visual-based localization: On the benefit of heterogeneous                             PR                            2018   [#piasco2018survey]_          `[PDF] <https://www.sciencedirect.com/science/article/abs/pii/S0031320317303448>`_
Local and Global Methods for Registering 2D Image Sets and 3D Point Clouds                         Preprint                      2015   [#paudel2015local]_           `[PDF] <https://www.theses.fr/2015DIJOS077>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================

4.2. Geometric 2D-3D features matching
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=======================================================================================================================   =============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                                               Venue                          Year   Ref                           Materials
=======================================================================================================================   =============================  =====  ============================  ==========================================================================================================================================================================
Automatic 3D to 2D registration for the photorealistic rendering of urban scenes                                          CVPR                           2005   [#liu2005automatic]_          `[PDF] <https://ieeexplore.ieee.org/document/1467433>`_
A systematic approach for 2D-image to 3D-range registration in urban environments                                         ICCV                           2008   [#liu2007systematic]_         `[PDF] <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.177.9122&rep=rep1&type=pdf>`_
Integrating automated range registration with multiview geometry for the photorealistic modeling of large-scale scenes    IJCV                           2008   [#stamos2008integrating]_     `[PDF] <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.177.9414&rep=rep1&type=pdf>`_
=======================================================================================================================   =============================  =====  ============================  ==========================================================================================================================================================================

----

4.3. Simultaneously camera pose estimation and 2D-3D correspondence estimation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=====================================================================================================     ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                               Venue                         Year   Ref                           Materials
=====================================================================================================     ============================  =====  ============================  ==========================================================================================================================================================================
Softposit: Simultaneous pose and correspondence determination                                             ECCV                          2001   [#david2004softposit]_        `[PDF] <http://users.umiacs.umd.edu/~daniel/daniel_papersfordownload/ijcvSoftPOSIT03.pdf>`_
Globally optimal 2D-3D registration from points or lines without correspondences                          ICCV                          2015   [#brown2015globally]_         `[PDF] <https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Brown_Globally_Optimal_2D-3D_ICCV_2015_paper.pdf>`_
A family of globally optimal branch-and-bound algorithms for 2D–3D correspondence-free registration       PR                            2019   [#brown2019family]_           `[PDF] <https://www.sciencedirect.com/science/article/pii/S0031320319301426>`_
Globally-Optimal Inlier Set Maximisation for Camera Pose and Correspondence Estimation                    TPAMI                         2018   [#campbell2018globally]_      `[PDF] <https://arxiv.org/abs/1709.09384>`_
The Alignment of the Spheres: Globally-Optimal Spherical Mixture Alignment for Camera Pose Estimation     CVPR                          2019   [#campbell2019alignment]_     `[PDF] <https://arxiv.org/abs/1812.01232>`_ 
=====================================================================================================     ============================  =====  ============================  ==========================================================================================================================================================================

----

4.4. Airborne (UAV) image to terriseal LiDAr scanner point cloud matching
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==================================================================================================================    ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                                           Venue                         Year   Ref                           Materials
==================================================================================================================    ============================  =====  ============================  ==========================================================================================================================================================================
Automatic registration of UAV-borne sequent images and LiDAR data                                                     ISPRS                         2015   [#yang2015automatic]_         `[PDF] <https://www.sciencedirect.com/science/article/abs/pii/S0924271615000180>`_
Automatic registration of panoramic image sequence and mobile laser scanning data using semantic features             ISPRS                         2018   [#li2018automatic]_           `[PDF] <https://www.sciencedirect.com/science/article/abs/pii/S0924271617303829>`_
Automatic Registration of Optical Images with Airborne LiDAR Point Cloud in Urban Scenes                              Sensors                       2019   [#peng2019automatic]_         `[PDF] <https://www.mdpi.com/1424-8220/19/5/1086>`_
An Accurate TLS and UAV Image Point Clouds Registration Method for Deformation Detection of Chaotic Hillside Areas    RS                            2019   [#zang2019accurate]_          `[PDF] <https://www.mdpi.com/2072-4292/11/6/647>`_
==================================================================================================================    ============================  =====  ============================  ==========================================================================================================================================================================

----

5. Key Conferences/Workshops/Journals
-------------------------------------

5.1. Conferences & Workshops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^


`IEEE International Conference on Computer Vision and Pattern Recognition <http://cvpr2020.thecvf.com/>`_

`IEEE International Conference on Computer Vision <http://iccv2019.thecvf.com/>`_

`European Conference on Computer Vision <https://eccv2020.eu/>`_

`IEEE International Conference on Robotics and Automation  <https://www.icra2020.org/>`_

`International Conference on 3D Vision <http://3dv19.gel.ulaval.ca/>`_

`Winter Conference on Applications of Computer Vision <https://wacv20.wacv.net/>`_

5.2. Journals
^^^^^^^^^^^^^

`IEEE Transactions on Pattern Analysis and Machine Intelligence <https://www.computer.org/csdl/journal/tp>`_

`International Journal of Computer Vision <https://link.springer.com/journal/11263>`_

`ISPRS Journal of Photogrammetry and Remote Sensing <https://www.journals.elsevier.com/isprs-journal-of-photogrammetry-and-remote-sensing>`_

----

References
----------
.. [#hongdong2018] 李宏东， 周定富， 刘流. 自定位技术在自动驾驶中的应用. 中国计算机学会通讯，14卷 8期， 2018
.. [#piasco2018survey] Piasco N, Sidibé D, Demonceaux C, et al. A survey on visual-based localization: On the benefit of heterogeneous data. Pattern Recognition, 2018, 74: 90-109.

.. [#paudel2015local] Paudel D P. Local and global methods for registering 2D image sets and 3D point clouds. Dijon, 2015.

.. [#liu2005automatic] Liu L, Stamos I. Automatic 3D to 2D registration for the photorealistic rendering of urban scene. IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'05). IEEE, 2005, 2: 137-143.

.. [#liu2007systematic] Liu L, Stamos I. A systematic approach for 2D-image to 3D-range registration in urban environments. IEEE 11th International Conference on Computer Vision. IEEE, 2007: 1-8.

.. [#stamos2008integrating] Stamos I, Liu L, Chen C, et al. Integrating automated range registration with multiview geometry for the photorealistic modeling of large-scale scenes. International Journal of Computer Vision, 2008, 78(2-3): 237-260.

.. [#david2004softposit] David P, Dementhon D, Duraiswami R, et al. SoftPOSIT: Simultaneous pose and correspondence determination. International Journal of Computer Vision, 2004, 59(3): 259-284.

.. [#brown2015globally] Brown M, Windridge D, Guillemaut J Y. Globally optimal 2D-3D registration from points or lines without correspondences. IEEE International Conference on Computer Vision. 2015: 2111-2119.

.. [#brown2019family] Brown M, Windridge D, Guillemaut J Y. A family of globally optimal branch-and-bound algorithms for 2D–3D correspondence-free registration. Pattern Recognition, 2019, 93: 36-54.

.. [#campbell2018globally] Campbell D J, Petersson L, Kneip L, et al. Globally-Optimal Inlier Set Maximisation for Camera Pose and Correspondence Estimation. IEEE transactions on pattern analysis and machine intelligence, 2018.

.. [#campbell2019alignment] Campbell D, Petersson L, Kneip L, et al. The Alignment of the Spheres: Globally-Optimal Spherical Mixture Alignment for Camera Pose Estimation. IEEE Conference on Computer Vision and Pattern Recognition. 2019: 11796-11806.

.. [#yang2015automatic] Yang B, Chen C. Automatic registration of UAV-borne sequent images and LiDAR data[J]. ISPRS Journal of Photogrammetry and Remote Sensing, 2015, 101: 262-274.

.. [#li2018automatic] Li J, Yang B, Chen C, et al. Automatic registration of panoramic image sequence and mobile laser scanning data using semantic features. ISPRS journal of photogrammetry and remote sensing, 2018, 136: 41-57.

.. [#peng2019automatic] Peng S, Ma H, Zhang L. Automatic Registration of Optical Images with Airborne LiDAR Point Cloud in Urban Scenes Based on Line-Point Similarity Invariant and Extended Collinearity Equations. Sensors, 2019, 19(5): 1086.

.. [#zang2019accurate] Zang Y, Yang B, Li J, et al. An Accurate TLS and UAV Image Point Clouds Registration Method for Deformation Detection of Chaotic Hillside Areas. Remote Sensing, 2019, 11(6): 647.