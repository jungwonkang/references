# References - SLAM (main)

Revised on Mar 6 2021

<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Survey

#### Overall
- [A survey of simultaneous localization and mapping with an envision in 6G wireless networks](https://arxiv.org/abs/1909.05214)
- [An Overview of Perception and Decision-Making in Autonomous Systems in the Era of Learning](https://arxiv.org/abs/2001.02319)
- [Past, present, and future of SLAM: towards the robust-perception age](https://arxiv.org/pdf/1606.05830.pdf)
- [Simultaneous Localization and Mapping: a survey of current trends in autonomous driving](https://hal.archives-ouvertes.fr/hal-01615897/file/2017-simultaneous_localization_and_mapping_a_survey_of_current_trends_in_autonomous_driving.pdf)

#### Visual-based
- [Keyframe-based monocular SLAM: design, survey, and future directions](https://arxiv.org/pdf/1607.00470.pdf)
- [Visual Simultaneous Localization and Mapping: a Survey]
- [Visual SLAM algorithms: A survey from 2010 to 2016]
- [Visual odometry and SLAM: past, present, and the robust-perception age (by Davide Scaramuzza)](https://www.rsj.or.jp/databox/international/iros16tutorial_2.pdf)

#### LiDAR-based
- [A survey of SLAM research based on LiDAR sensors](http://www.remedypublications.com/open-access/a-survey-of-slam-research-based-on-lidar-sensors-4870.pdf)

#### Deep Learning-based
- [A Survey on Deep Learning for Localization and Mapping_Towards the Age of Spatial Machine Intelligence](https://arxiv.org/abs/2006.12567)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## LiDAR Odometry and Mapping

#### LOAM original
- LOAM: Lidar Odometry and Mapping in Real-time (RSS 2014)
- Real-time Depth Enhanced Monocular Odometry (IROS 2014)
- Visual-lidar Odometry and Mapping_Low-drift, Robust, and Fast (ICRA 2015)
- Laser-visual-inertial Odometry and Mapping with High Robustness and Low Drift (JFR2018)

#### LOAM variant (using new feature)
- [S-LOAM] Semantic Lidar Odometry and Mapping for Forest Inventory (ICRA 2020)
- [I-LOAM] Intensity Enhanced LiDAR Odometry and Mapping (UR 2020)

#### LOAM variant (adding loop-closing)
- [Lego-LOAM] Lightweight and ground-optimized lidar odometry and mapping on variable terrain (IROS 2018)
- LiDAR Odometry and Mapping with Loop-closure Detection Based Correction (ICMA 2019)
- [LOAM + SegMatch] Optimized LOAM Using Ground Plane Constraints and SegMatch-Based Loop Detection (Sensors 2019)

#### LOAM variant (adding vision)
- A Tight Coupling of Vision-Lidar Measurements for an Effective Odometry (IV 2019)
- [VISO2 + LOAM] Loose coupling visual-lidar odometry by combining VISO2 and LOAM (CCC 2017)


#### LOAM variant (designed for a specific sensor)
- [LOAM Livox] A fast, robust, high-precision LiDAR odometry and mapping package for LiDARs of small FoV (ICRA 2020)

#### Code
- [laboshinl/loam_velodyne] https://github.com/laboshinl/loam_velodyne
- [RobustFieldAutonomyLab/LeGO-LOAM] https://github.com/RobustFieldAutonomyLab/LeGO-LOAM
- [A-LOAM] https://github.com/HKUST-Aerial-Robotics/A-LOAM
- [F-LOAM] https://github.com/wh200720041/floam
- https://github.com/stevenliu216/568-Final-Project
- [loam code noted in Chinese] https://github.com/cuitaixiang/LOAM_NOTED
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Deep-based LiDAR odometry and mapping

- LO-Net: Deep Real-time Lidar Odometry
- CAE-LO: LiDAR Odometry Leveraging Fully Unsupervised Convolutional Auto-Encoder for Interest Point Detection and Feature Description
  - https://github.com/SRainGit/CAE-LO
- DeepLO: Geometry-Aware Deep LiDAR Odometry
- DeepPCO: End-to-End Point Cloud Odometry through Deep Parallel Neural Network
- DeLiO: Decoupled LiDAR Odometry
- DeLORA: Self-supervised Learning of LiDAR Odometry for Robotic Applications
  - https://github.com/leggedrobotics/DeLORA
- DMLO: Deep Matching LiDAR Odometry
- SelfVoxeLO: Self-supervised LiDAR Odometry with Voxel-based Deep Neural Networks
- PSF-LO_Parameterized Semantic Features Based Lidar Odometry
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [LiDAR-based SLAM] SuMa++

#### SuMa++ original
- [SuMa] Efficient Surfel-Based SLAM using 3D Laser Range Data in Urban Environments (RSS 2018)
- SuMa++: Efficient LiDAR-based Semantic SLAM (IROS 2019)
  - https://github.com/PRBonn/semantic_suma
  
#### Loop closing
- OverlapNet: Loop Closing for LiDAR-based SLAM (RSS 2020)
  - https://github.com/PRBonn/OverlapNet
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [LiDAR-based SLAM] MOLA
- [A Modular Optimization Framework for Localization and Mapping](http://www.roboticsproceedings.org/rss15/p43.pdf)
  - github: https://github.com/MOLAorg/mola
  - presentation: https://youtu.be/qwh8hGEJSlA
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [LiDAR-based SLAM] Cartographer

#### Cartographer original
- Real-Time Loop Closure in 2D LIDAR SLAM

#### Cartographer variant
- Cartographer SLAM Method for Optimization with an Adaptive Multi-Distance Scan Scheduler
- Continuous-Time SLAM_Improving Googles Cartographer 3D Mapping
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [LiDAR-based SLAM]
- MULLS: Versatile LiDAR SLAM via Multi-metric Linear Least Square (ICRA 2021)
  - git: https://github.com/YuePanEdward/MULLS
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [LiDAR-based SLAM]
- LiTAMIN2: Ultra Light LiDAR-based SLAM using Geometric Approximation applied with KL-Divergence (ICRA 2021)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [LiDAR-inertial SLAM]
- https://github.com/KIT-ISAS/lili-om
- https://github.com/Livox-SDK/LIO-Livox
- https://github.com/ChaoqinRobotics/LINS---LiDAR-inertial-SLAM
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Loop closing for LiDAR-SLAM

- OverlapNet: Loop Closing for LiDAR-based SLAM (RSS 2020)
  - https://github.com/PRBonn/OverlapNet

#### SegMatch series
- SegMatch: Segment based loop-closure for 3D point clouds
- SegMap: 3D Segment Mapping using Data-Driven Descriptors
- Incremental-segment-based localization in 3-D point clouds (RAL 2018)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## LiDAR-based Works using NDT

#### NDT original
- The Normal Distributions Transform: A New Approach to Laser Scan Matching
- [Thesis] The Three-Dimensional Normal-Distributions Transform — an Efficient Representation for Registration, Surface Analysis, and Loop Detection

#### Semantic NDT
- Semantic-assisted 3D Normal Distributions Transform for scan registration in environments with limited structure (IROS 2017)
- Integrating deep semantic segmentation into 3-D point cloud registration (RAL 2018)

#### Works using NDT (Nagoya University)
- Localization based on multiple visual-metric maps
- Monocular vision-based localization using ORB-SLAM with LiDAR-aided mapping in real_world robot challenge
- Robust Localization Using 3D NDT Scan Matching with Experimentally Determined Uncertainty and Road Marker Matching

#### Works using NDT
- Normal Distributions Transform Traversability Maps_LIDAR-Only Approach for Traversability Mapping in Outdoor Environments (JFR 2016)
- Direct Depth SLAM_Sparse Geometric Feature Enhanced Direct Depth SLAM System for Low-Texture Environments (sensors 2018)
- Semantic Point Cloud Mapping of LiDAR Based on Probabilistic Uncertainty Modeling for Autonomous Driving (sensors 2020)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Visual-LiDAR SLAM
- [Vision-enhanced LiDAR odometry and mapping (Master's thesis, Carnegie Mellon University)](https://www.ri.cmu.edu/pub_files/2016/8/DLL-thesis.pdf)
- [A real-time method for depth enhanced visual odometry](https://frc.ri.cmu.edu/~zhangji/publications/AURO_2017.pdf)
- [LIMO: LiDAR monocular visual odometry](https://arxiv.org/pdf/1807.07524.pdf)
- DVL-SLAM: Sparse depth enhanced direct visual-LiDAR SLAM
- [Stereo Visual Inertial LiDAR Simultaneous Localization and Mapping](https://arxiv.org/abs/1902.10741)
- A Simultaneous Localization and Mapping (SLAM) Framework for 2.5D Map Building Based on Low-Cost LiDAR and Vision Fusion
- [RTAB-MAP] RTAB-Map as an Open-Source Lidar and Visual SLAM Library for Large-Scale and Long-Term Online Operation (JFR 2019)
  - http://introlab.github.io/rtabmap/
- LIMO: LiDAR monocular visual odometry

#### Panoramic Vision-LiDAR SLAM
- 3D Scene Reconstruction Using Omnidirectional Vision and LiDAR A Hybrid Approach
- Line-Based Registration of Panoramic Images and LiDAR Point Clouds for Mobile Mapping
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [Visual SLAM] ORB SLAM

#### ORB SLAM original
- [ORB-SLAM2] ORB-SLAM2: an Open-Source SLAM System for Monocular, Stereo and RGB-D Cameras
- [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)
  - https://pythonawesome.com/an-accurate-open-source-library-for-visual/

#### ORB-SLAM variant (using semantic info)
- DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments (IROS 2018)
  - https://github.com/ivipsourcecode/DS-SLAM
- Dynamic Scene Semantics SLAM Based on Semantic Segmentation (IEEE Access)
- SaD-SLAM: A Visual SLAM Based on Semantic and Depth Information (IROS 2020)

#### ORB-SLAM variant (using LiDAR data)
- Monocular vision-based localization using ORB-SLAM with LiDAR-aided mapping in real_world robot challenge
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [Visual SLAM] Panoramic Vision based SLAM
- Monocular Visual Odometry in Urban Environments Using an Omnidirectional Camera (IROS 2008)	[[movie]](https://youtu.be/cq63ItHfv50)
- GPS-Supported Visual SLAM with a Rigorous Sensor Model for a Panoramic Camera in Outdoor Environments (Sensors 2012)
- PVO: Panoramic Visual Odometry (ICARM 2018) [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8610700&tag=1)] [[movie](https://youtu.be/CdPFPKPT4CE)] [[git](https://github.com/MinjieLin/panorama_slam)]
  - [Ricoh Theta V](https://theta360.com/en/about/theta/v.html)
- [PAN-SLAM] Panoramic SLAM from a multiple fisheye camera rig (2020)
  - http://gpcv.whu.edu.cn/data/panslam.html
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [Visual SLAM]
- OpenVSLAM
- [GSLAM (A General SLAM Framework and BenchMark)](https://github.com/zdzhaoyong/GSLAM)
- OV2: A Fully Online and Versatile Visual SLAM for Real-Time Applications
  - https://github.com/ov2slam/ov2slam
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Visual Odometry
- [DSO](https://vision.in.tum.de/research/vslam/dso?redirect=1)
  - https://github.com/JakobEngel/dso
  - https://github.com/JakobEngel/dso_ros
- SVO
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Visual-Inertial SLAM
- VINS-Mono
- Maplab
  - MAPLAB_An Open Framework for Research in Visual-inertial Mapping and Localization
  - Robust Visual Inertial Odometry Using a Direct EKF-Based Approach
- OpenVINS: A Research Platform for Visual-Inertial Estimation
  - https://github.com/rpng/open_vins
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Code
- [pySLAM](https://github.com/luigifreda/pyslam)
  - https://pythonawesome.com/a-toy-implementation-of-a-visual-odometry-vo-pipeline-in-python-2/
- https://github.com/gisbi-kim/PyICP-SLAM
- https://github.com/dongjing3309/minisam
- https://github.com/TixiaoShan/LIO-SAM
  - https://github.com/gisbi-kim/SC-LIO-SAM
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Dataset
- Complex Urban Dataset with Multi-level Sensors from Highly Diverse Urban Environments (IJRR 2019)
- Complex Urban LiDAR Data Set (ICRA 2018)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Evaluation
- A Tutorial on Quantitative Trajectory Evaluation for Visual(-Inertial) Odometry
  - https://github.com/uzh-rpg/rpg_trajectory_evaluation
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Uncategorized yet
- LM-Reloc_Levenberg-Marquardt Based Direct Visual Relocalization
- Closed-loop benchmarking of stereo visual-intertial SLAM sytems
- gradSLAM: Automagically differentiable SLAM
- PTAM, DTAM
- LSD
- [ICRA2020] Lidar-Monocular Visual Odometry using Point and Line Features
- [ICRA2020] Visual Odometry Revisited_What Should Be Learnt
- f-BRS: Rethinking Backpropagating Refinement for Interactive Segmentation
- WoodScape: A multi-task, multi-camera fisheye dataset for autonomous driving
- DDAD - Dense Depth for Autonomous Driving
  - https://github.com/TRI-ML/DDAD
- [ORB + LOAM] https://github.com/306327680/loam-loop-closure
- https://www.emesent.io/
  - https://research.csiro.au/robotics/our-work/research-areas/3d-lidar-mapping/



