# References

Started to write on July 1 2019
<br/>


### Lane detection
*Survey*
- https://github.com/amusi/awesome-lane-detection
- https://paperswithcode.com/task/lane-detection/codeless

*CNN*
- 3D Lanenet: end-to-end 3d multiple lane detection
- An efficient encoder-decoder cnn architecture for reliable multilane detection in real time
- Reliable multilane detection and classification by utilizing cnn as a regression network
- Towards end-to-end lane detection_an instance segmentation approach
- End-to-end lane detection through differentiable least-squares fitting
- VPGnet: vanishing point guided network for lane and road marking detection and recognition

*RNN*
- Deep neural network for structural prediction and lane detection in traffic scene
- Lanenet: real-time lane detection networks for autonomous driving
- Robust lane detection from continuous driving scenes using deep neural networks

*LiDAR*
- Hierarchical recurrent attention networks for structured online maps
[[Tensorflow](https://github.com/shawnspace/HRAN)]

*Uncategorized yet*
- Deep semantic lane segmentation for mapless driving
- Find your own way_weakly-supervised segmentation of path proposals for urban autonomy
- Robust road marking detection and recognition using density-based grouping and machine learning techniques
- Spatial as deep_spatial cnn for traffic scene understanding
- FastDraw: addressing the long tail of lane detection by adapting a sequential prediction network
<br/>



### Lane detection with code
- Towards end-to-end lane detection: an instance segmentation approach 
[[Tensorflow1](https://github.com/MaybeShewill-CV/lanenet-lane-detection)]
[[Tensorflow2](https://maybeshewill-cv.github.io/lanenet-lane-detection/)]
[[PyTorch](https://github.com/harryhan618/LaneNet)]
- End-to-end lane detection through differentiable least-squares fitting
[[PyTorch](https://github.com/wvangansbeke/LaneDetection_End2End)]
- TuSimple dataset road lane instance segmentation with PyTorch, ROS, ENet, SegNet and Discriminative Loss
[[PyTorch](https://github.com/jaeoh2/Road-Lane-Instance-Segmentation-PyTorch)]
- Spatial as deep_spatial cnn for traffic scene understanding
[[PyTorch](https://github.com/harryhan618/SCNN_Pytorch)]
<br/>


### Rail detection
- Efficient rail area detection using convolutional neural network
- [Detecting rails in imagesfrom a train-mounted thermal camera using a convolutional neural network](https://liu.diva-portal.org/smash/get/diva2:1111486/FULLTEXT01.pdf)
<br/>


### 2D bounding box detection
- https://handong1587.github.io/deep_learning/2015/10/09/object-detection.html
- [Recent advances in object detection in the age of deep convolutional neural networks](https://hal.archives-ouvertes.fr/hal-01869779/document)
- [A paper list of object detection using deep learning](https://pythonawesome.com/a-paper-list-of-object-detection-using-deep-learning/)
- [PVANet: lightweight deep neural networks for real-time object detection](https://youtu.be/TYDGTnxUGHQ)
- [DisNet: A novel method for distance estimation from monocular camera](https://project.inria.fr/ppniv18/files/2018/10/presentationHaseeb.pdf)
<br/>


### 2D Semantic segmentation survey
- A review on deep learning techniques applied to semantic segmentation
- Survey on semantic segmentation using deep learning techniques
<br/>


### Real-time semantic segmentation
- ENet: a deep neural architecture for real-time semantic segmentation
- [ICNet for real-time semantic segmentation on high-resolution images](https://hszhao.github.io/projects/icnet/) 
[[Caffe](https://github.com/hszhao/ICNet)]
- ERFNet: Efficient Residual Factorized ConvNet forReal-time Semantic Segmentation
[[PyTorch](https://github.com/hagerrady13/ERFNet-PyTorch)]
- [RTSeg: real-time semantic segmentation comparative study](https://github.com/MSiam/TFSegmentation)
  - [A comparative study of real-time semantic segmentation for autonomous driving](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w12/Siam_A_Comparative_Study_CVPR_2018_paper.pdf)
- ESPNet: efficient spatial pyramid of dilated convolutions for semantic segmentation
- Guided upsampling network for real-time semantic segmentation
<br/>


### General obstacle detection
- Real-time category-based and general obstacle detection for autonomous driving 
[[Paper](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Garnett_Real-Time_Category-Based_and_ICCV_2017_paper.pdf)]
[[PyTorch](https://github.com/869369851/Real-time-category-based-and-general-obstacle-detection-for-autonomous-driving)]
- J-MOD2: joint monocular obstacle detection and depth estimation
- StixelNet: a deep convolutional network forobstacle detection and road segmentation
- Real-time category-based and general obstacle detection for autonomous driving
- MultiNet: real-time joint semantic reasoning for autonomous driving
<br/>


### Dataset
- [RailSem19: a dataset for semantic rail scene understanding](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Autonomous%20Driving/Zendel_RailSem19_A_Dataset_for_Semantic_Rail_Scene_Understanding_CVPRW_2019_paper.pdf)
  - [WildDash benchmark](http://www.wilddash.cc/)
<br/>


### Etc
- Semantic instance segmentation with a discriminative loss function
[[Pytorch](https://github.com/Wizaron/instance-segmentation-pytorch)]
- Pseudo-lidar from visual depth estimation bridging the gap in 3d object detection for autonomous driving
- [ROS package for the perception (sensor processing, detection, tracking and evaluation) of the KITTI vision benchmark suite](https://github.com/appinho/SARosPerceptionKitti)
- [A list of references on lidar point cloud processing for autonomous driving](https://github.com/beedotkiran/Lidar_For_AD_references)
- [SECOND for KITTI/NuScenes object detection](https://github.com/traveller59/second.pytorch)
- [3D object detection for autonomous driving using deep learning](https://github.com/fregu856/3DOD_thesis)
<br/>


### Selected papers (June 14 2019)
*Lane detection*
- Towards end-to-end lane detection: an instance segmentation approach
- ENet: a deep neural network architecture for real-time semantic segmentation

*3D bounding box detection*
- Pointpillars: fast encoders for object detection from point clouds [[PyTorch](https://github.com/nutonomy/second.pytorch)]

*Depth estimation*
- Real-time joint semantic segmentation and depth estimation using asymmetric annotations
- Real-time monocular depth estimation using synthetic data with domain adaptation via image style transfer
- Fastdepth: fast monocular depth estimation on embedded systems
- Self-supervised learning for single view depth and surface normal estimation
- Superdepth self-supervised, super-resolved monocular depth estimation

*General obstacle detection*
- Monocular semantic occupancy grid mapping with convolutional variational encoder-decoder networks [[PyTorch](https://github.com/Chenyang-Lu/mono-semantic-occupancy)]
- Building a winning self-driving car in six months
<br/>



### From ICRA 2019
*Benchmark*
- SLAMBench 3.0: Systematic Automated Reproducible Evaluation of SLAM Systems for Robot Vision Challenges and Scene Understanding
- The H3D Dataset for Full-Surround 3D Multi-Object Detection and Tracking in Crowded Urban Scenes
- BLVD: Building a Large-Scale 5D Semantics Benchmark for Autonomous Driving
<br/>

*Segmentation*
- SqueezeSegV2: Improved Model Structure and Unsupervised Domain Adaptation for Road-Object Segmentation from a LiDAR Point Cloud
- Segmenting Unknown 3D Objects from Real Depth Images Using Mask R-CNN Trained on Synthetic Data
- Semi Supervised Deep Quick Instance Detection and Segmentation
- Bonnet: An Open-Source Training and Deployment Framework for Semantic Segmentation in Robotics Using CNNs
- Adapting Semantic Segmentation Models for Changes in Illumination and Camera Perspective
- Dynamic Risk Density for Autonomous Navigation in Cluttered Environments without Object Detection
- An Approach for Semantic Segmentation of Tree-Like Vegetation
- DFNet: Semantic Segmentation on Panoramic Images with Dynamic Loss Weights and Residual Fusion Block
<br/>

*Point cloud segmentation*
- MVX-Net: Multimodal VoxelNet for 3D Object Detection
- Hierarchical Depthwise Graph Convolutional Neural Network for 3D Semantic Segmentation of Point Clouds
<br/>

*Object detection (2D)*
- Dual Refinement Network for Single-Shot Object Detection
<br/>

*Object detection (3D)*
- SEG-VoxelNet for 3D Vehicle Detection from RGB and LiDAR Data
- Focal Loss in 3D Object Detection
<br/>

*General obstacle detection*
- Monocular Semantic Occupancy Grid Mapping with Convolutional Variational Encoder-Decoder Networks
- Where Should I Walk? Predicting Terrain Properties from Images Via Self-Supervised Learning
- Building a Winning Self-Driving Car in Six Months
- Dynamic Hilbert Maps: Real-Time Occupancy Predictions in Changing Environments
- Long-Term Occupancy Grid Prediction Using Recurrent Neural Networks
<br/>

*Depth estimation*
- Unsupervised Learning of Monocular Depth and Ego-Motion Using Multiple Masks
- Real-Time Joint Semantic Segmentation and Depth Estimation Using Asymmetric Annotations
- Geo-Supervised Visual Depth Prediction
- Self-Supervised Learning for Single View Depth and Surface Normal Estimation
- GANVO: Unsupervised Deep Monocular Visual Odometry and Depth Estimation with Generative Adversarial Networks
- DispSegNet: Leveraging Semantics for End-To-End Learning of Disparity Estimation from Stereo Imagery
- Self-Supervised Sparse-To-Dense: Self-Supervised Depth Completion from LiDAR and Monocular Camera
- Anytime Stereo Image Depth Estimation on Mobile Devices
- FastDepth: Fast Monocular Depth Estimation on Embedded Systems
- UWStereoNet: Unsupervised Learning for Depth Estimation and Color Correction of Underwater Stereo Imagery
- SuperDepth: Self-Supervised, Super-Resolved Monocular Depth Estimation
<br/>

*SLAM framework*
- Visual-Inertial Navigation: A Concise Review
- IN2LAMA: INertial Lidar Localisation and MApping
<br/>

*UWB*
- ATLAS FaST: Fast and Simple Scheduled TDOA for Reliable Ultra-Wideband Localization
- A Kalman Filter-Based Algorithm for Simultaneous Time Synchronization and Localization in UWB Networks
- Estimating the Localizability in Tunnel-Like Environments Using LiDAR and UWB
- Integrated UWB-Vision Approach for Autonomous Docking of UAVs in GPS-Denied Environments
- UWB/LiDAR Fusion for Cooperative Range-Only SLAM
<br/>

*Etc*
- Learning Scene Geometry for Visual Localization in Challenging Conditions
- Learning Long-Range Perception Using Self-Supervision from Short-Range Sensors and Odometry
<br/>


### From CVPR-W 2019 [[all](http://openaccess.thecvf.com/menu.py)] [[CVPR-W 2019](http://openaccess.thecvf.com/CVPR2019_workshops/CVPR2019_Autonomous_Driving.py)]
- Attentional PointNet for 3D-Object Detection in Point Clouds
- Complexer YOLO Real-Time 3D Object Detection and Tracking on Semantic Point Clouds
- DSCnet Replicating Lidar Point Clouds with Deep Sensor Cloning
- MultiNet++: Multi-Stream Feature Aggregation and Geometric Loss Strategy for Multi-Task Learning
- RailSem19: A Dataset for Semantic Rail Scene Understanding
- Sensor Fusion for Joint 3D Object Detection and Semantic Segmentation
- Spatial Sampling Network for Fast Scene Understanding
- Unsupervised Domain Adaptation for Semantic Segmentation of Urban Scenes
<br/>



