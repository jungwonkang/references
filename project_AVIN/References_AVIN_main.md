# References

Started to write on July 1 2019
<br/>

### Dataset
- [RailSem19: a dataset for semantic rail scene understanding](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Autonomous%20Driving/Zendel_RailSem19_A_Dataset_for_Semantic_Rail_Scene_Understanding_CVPRW_2019_paper.pdf)
  - [WildDash benchmark](http://www.wilddash.cc/)
- [A dataset for lane instance segmentation in urban environments](http://openaccess.thecvf.com/content_ECCV_2018/html/Brook_Roberts_A_Dataset_for_ECCV_2018_paper.html)
- [FRSign - French Railway Signalling Dataset](https://frsign.irt-systemx.fr/)
- [VisualData Discovery](https://www.visualdata.io/)
<br/>


### Lane detection
*Survey*
- https://github.com/amusi/awesome-lane-detection
- https://paperswithcode.com/task/lane-detection/codeless
<br/>

*CNN-based*
- 3D Lanenet: end-to-end 3d multiple lane detection
- An efficient encoder-decoder cnn architecture for reliable multilane detection in real time
- Reliable multilane detection and classification by utilizing cnn as a regression network
- Towards end-to-end lane detection_an instance segmentation approach
- End-to-end lane detection through differentiable least-squares fitting
- VPGnet: vanishing point guided network for lane and road marking detection and recognition
- FastDraw: addressing the long tail of lane detection by adapting a sequential prediction network
- Spatial as deep_spatial cnn for traffic scene understanding
- [Multi-lane Detection Using Instance Segmentation and Attentive Voting](https://arxiv.org/abs/2001.00236)
<br/>

*RNN-based*
- Deep neural network for structural prediction and lane detection in traffic scene
- Lanenet: real-time lane detection networks for autonomous driving
- Robust lane detection from continuous driving scenes using deep neural networks
<br/>

*Using LiDAR*
- Hierarchical recurrent attention networks for structured online maps
[[Tensorflow](https://github.com/shawnspace/HRAN)]
- Real-Time Road Lane Detection in Urban Areas Using LiDAR Data
<br/>

*Using Vision + LiDAR*
- Deep multi-sensor lane detection
<br/>

*Lane detection with code*
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

*Uncategorized yet*
- Deep semantic lane segmentation for mapless driving
- Robust road marking detection and recognition using density-based grouping and machine learning techniques
<br/>



### Rail detection
*Deep*
- Efficient rail area detection using convolutional neural network
- [Detecting rails in images from a train-mounted thermal camera using a convolutional neural network](https://liu.diva-portal.org/smash/get/diva2:1111486/FULLTEXT01.pdf)
<br/>

*Non-Deep*
- Multi-railway track and turnout region recognition using mobile laser scanning data
- Obstacle-free range determination for rail track maintenance vehicles
- Automatic extraction of railroad centerlines from mobile laser scanning data
- [turnout] A vision based condition monitoring approach for rail switch and level crossing using hierarchical svm in railways
- [turnout] Detection of rail switch passages through image processing on railway line and use of condition-monitoring approach
- [turnout] Efficient railway tracks detection and turnouts recognition method using hog features
- [turnout] Rail and turnout detection using gradient information and template matching
- Vision based rail track and switch recognition for self-localization of trains in a rail network
- A Vision-Based Approach for Rail Extraction and its Application in a Camera Pan-Tilt Control System
- A Vision-Based Approach for Tramway Rail Extraction
<br/>


### Semantic segmentation
*Real-time semantic segmentation1*
- ENet: a deep neural architecture for real-time semantic segmentation
- [ICNet for real-time semantic segmentation on high-resolution images](https://hszhao.github.io/projects/icnet/) 
[[Caffe](https://github.com/hszhao/ICNet)]
- ERFNet: Efficient Residual Factorized ConvNet for Real-time Semantic Segmentation
[[PyTorch](https://github.com/hagerrady13/ERFNet-PyTorch)]
- [RTSeg: real-time semantic segmentation comparative study](https://github.com/MSiam/TFSegmentation)
  - [A comparative study of real-time semantic segmentation for autonomous driving](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w12/Siam_A_Comparative_Study_CVPR_2018_paper.pdf)
- ESPNet: efficient spatial pyramid of dilated convolutions for semantic segmentation
- Guided upsampling network for real-time semantic segmentation
<br/>

*Real-time semantic segmentation2*
- https://paperswithcode.com/sota/real-time-semantic-segmentation-on-cityscapes
- BiSeNet: Bilateral Segmentation Network for Real-time Semantic Segmentation
- In Defense of Pre-trained ImageNet Architectures for Real-time Semantic Segmentation of Road-driving Images
- ESNet: An Efficient Symmetric Network for Real-time Semantic Segmentation
- LEDNet: A Lightweight Encoder-Decoder Network for Real-Time Semantic Segmentation
- HarDNet: A Low Memory Traffic Network (iccv 2019)
  - https://github.com/PingoLH/Pytorch-HarDNet
  - https://github.com/PingoLH/FCHarDNet
- [FasterSeg: Searching for Faster Real-time Semantic Segmentation](https://arxiv.org/abs/1912.10917)
<br/>

*Survey*
- A review on deep learning techniques applied to semantic segmentation
- Survey on semantic segmentation using deep learning techniques
- Survey of recent progress in semantic imagesegmentation with CNNs
- [Deep Multi-modal Object Detection and Semantic Segmentation for Autonomous Driving: Datasets, Methods, and Challenges](https://boschresearch.github.io/multimodalperception/)
- A survey on 3d object detection methods for autonomous driving applications
- Deep learning for generic object detection: A survey

*Written by Sorin Grigorescu*
- [A survey of deep learning techniques for autonomous driving](https://arxiv.org/abs/1910.07738)
- [Deep Grid Net (DGN)_A Deep Learning System for Real-Time Driving Context Understanding](https://arxiv.org/abs/1901.05203)
<br/>

*Semantic segmentation*
- https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes
- [Gated-SCNN: Gated Shape CNNs for Semantic Segmentation](https://www.profillic.com/paper/arxiv:1907.05740?fbclid=IwAR0P6pPt3ApCkR4AmWgs7__TFcuiImBKRJixU8BlE_HzldydVP-kgJFkLbU)
<br/>


### Object detection
*Survey*
- [Object Detection in 20 Years: A Survey](https://arxiv.org/pdf/1905.05055.pdf)

*2D bounding box detection*
- https://handong1587.github.io/deep_learning/2015/10/09/object-detection.html
- [Recent advances in object detection in the age of deep convolutional neural networks](https://hal.archives-ouvertes.fr/hal-01869779/document)
- [A paper list of object detection using deep learning](https://pythonawesome.com/a-paper-list-of-object-detection-using-deep-learning/)
- [PVANet: lightweight deep neural networks for real-time object detection](https://youtu.be/TYDGTnxUGHQ)
- [DisNet: A novel method for distance estimation from monocular camera](https://project.inria.fr/ppniv18/files/2018/10/presentationHaseeb.pdf)
<br/>

*3D bounding box detection*
- Pointpillars: fast encoders for object detection from point clouds [[PyTorch](https://github.com/nutonomy/second.pytorch)]
- [SECOND for KITTI/NuScenes object detection](https://github.com/traveller59/second.pytorch)
- [3D object detection for autonomous driving using deep learning](https://github.com/fregu856/3DOD_thesis)
<br/>

*Etc*
- [Monocular 3D Object Detection with Pseudo-LiDAR Point Cloud](https://www.profillic.com/paper/arxiv:1903.09847?fbclid=IwAR13HGHYG1mZaqW3Tqxgc9L2qbaa4f2cSjaYBSTZfLDc5x5k51qNUWplNfA)
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


### Etc
- Multi-modal object detection and localization for high integrity driving assistance
- Road scene understanding by occupancy grid learning from sparse radar clusters using semantic segmentation
- Semantic instance segmentation with a discriminative loss function
[[Pytorch](https://github.com/Wizaron/instance-segmentation-pytorch)]
- Pseudo-lidar from visual depth estimation bridging the gap in 3d object detection for autonomous driving
- [ROS package for the perception (sensor processing, detection, tracking and evaluation) of the KITTI vision benchmark suite](https://github.com/appinho/SARosPerceptionKitti)
- [A list of references on lidar point cloud processing for autonomous driving](https://github.com/beedotkiran/Lidar_For_AD_references)
- Multimodal unsupervised image-to-image translation
- [Distant vehicle detection using radar and vision](https://arxiv.org/abs/1901.10951)
- Off-road drivable area extraction using 3d LiDAR data
- Convolutional Recurrent Network for Road Boundary Extraction
- The Autonomous Train (D Trentesaux)
<br/>


### Etc (survey)
- A Survey of Autonomous Driving: Common Practices and Emerging Technologies
- A Systematic Review of Perception System and Simulators for Autonomous Vehicles Research
- Recent advances in connected and automated vehicles
- [MIT Advanced Vehicle Technology Study: Large-Scale Naturalistic Driving Study of Driver Behavior and Interaction With Automation](https://arxiv.org/pdf/1711.06976.pdf)
- [Deep learning for 3d point clouds: a survey](https://arxiv.org/pdf/1912.12033v1.pdf)
- [Self-Driving Cars: A Survey](https://arxiv.org/pdf/1901.04407.pdf)
<br/>


### Selected papers (June 14 2019)
*Depth estimation*
- Real-time joint semantic segmentation and depth estimation using asymmetric annotations
- Real-time monocular depth estimation using synthetic data with domain adaptation via image style transfer
- Fastdepth: fast monocular depth estimation on embedded systems
- Self-supervised learning for single view depth and surface normal estimation
- Superdepth self-supervised, super-resolved monocular depth estimation
<br/>

*General obstacle detection*
- Monocular semantic occupancy grid mapping with convolutional variational encoder-decoder networks [[PyTorch](https://github.com/Chenyang-Lu/mono-semantic-occupancy)]
- Building a winning self-driving car in six months
- Object Detection and Classification in Occupancy Grid Maps using Deep Convolutional Networks
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




### Updated (initially on Sept 22 2019)
*Path1*
- Convolutional Recurrent Network for Road Boundary Extraction
- Deep Learning Driven Visual Path Prediction froma Single Image
- Deep Semantic Lane Segmentation for Mapless Driving
- Find Your Own Way: Weakly-Supervised Segmentation of Path Proposals for Urban Autonomy
- LIDAR-based Driving Path Generation Using Fully Convolutional Neural Networks
- Predicting Ego-Vehicle Paths from Environmental Observations with a Deep Neural Network
<br/>

*Path2*
- Semantic Grid-Based Road Model Estimation for Autonomous Driving
- Generation of Probabilistic Graphs for Path Planningfrom Stochastic Map
- Lanelets: Efficient map representation for autonomous driving
- [MultiPath: Multiple probabilistic anchor trajectory hypotheses for behavior prediction](https://arxiv.org/pdf/1910.05449.pdf)
- [Diversity-aware vehicle motion prediction via latent semantic sampling](https://arxiv.org/abs/1911.12736)
- [Learning to predict ego-vehicle poses for sampling-based nonholonomic motion planning](https://arxiv.org/abs/1812.01127)
- [Gonet++: Traversability estimation via dynamic scene view synthesis](https://github.com/NHirose/VUNet)
- Dynamic path planning for autonomous driving on various roads with avoidance of static and moving obstacles
- A Survey of Motion Planning and Control Techniques for Self-driving Urban Vehicles
- NeuroTrajectory: A Neuroevolutionary Approach to Local State Trajectory Learning for Autonomous Vehicles
- [DRIVE Labs: How We’re Building Path Perception for Autonomous Vehicles](https://blogs.nvidia.com/blog/2019/04/30/drive-labs-path-perception/)
- Automated Process for Incorporating Drivable Path into Real-time Semantic Segmentation
- Winning the DARPA Grand Challenge
- Grid-Based Multi-Road-Course EstimationUsing Motion Planning
- Semantic Grid-Based Road Model Estimation for Autonomous Driving
- [Explaining the Hybrid A Star pathfinding algorithm for self driving cars](https://blog.habrador.com/2015/11/explaining-hybrid-star-pathfinding.html)
<br/>

*Attention1*
- Attention U-Net:Learning Where to Look for the Pancreas
- Attention to Scale: Scale-aware Semantic Image Segmentation
- Cross Attention Network for Semantic Segmentation
- Pyramid attention network for semantic segmentation
- Dual Attention Network for Scene Segmentation (cvpr 2019)
- Learning Lightweight Lane Detection CNNs by Self Attention Distillation
- PSANet: Point-wise Spatial Attention Network for Scene Parsing
- Using the wide range attention U Net for road segmentation
- Towards Accurate High Resolution SatelliteImage Semantic Segmentation
- Building Extraction from High-Resolution Aerial Imagery Using a Generative Adversarial Network with Spatial and Channel Attention Mechanisms
- Trajectory planning for autonomous vehicle in uncertainenvironment using evidential grid
<br/>

*Attention2*
- https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes
- Knowledge Distillation with Category-Aware Attention and Discriminant Logit Losses
- Attribute-Aware Attention Model for Fine-grained Representation Learning
- Localizing by Describing: Attribute-Guided Attention Localization for Fine-Grained Recognition
- LEDNet: A Lightweight Encoder-Decoder Network for Real-Time Semantic Segmentation
- DFANet: Deep Feature Aggregation for Real-Time Semantic Segmentation
- Connection Sensitive Attention U-NET for Accurate Retinal Vessel Segmentation
- [End-to-End Multi-Task Learning with Attention](https://github.com/lorenmt/mtan)
<br/>

*Cascade/Multi-stage semantic segmentation/Multi-task multi-stage*
- A Multi-Stage Multi-Task Neural Network forAerial Scene Interpretation and Geolocalization
- Roadmap Generation using a Multi-Stage Ensemble of Deep Neural Networks with Smoothing-Based Optimization
- Multi-stage Object Detection with Group Recursive Learning
- Hierarchical graph-based segmentation for extracting road networks from high-resolution satellite images
- An application of cascaded 3D fully convolutional networks for medical image segmentation
  - Hierarchical 3D fully convolutional networks for multi-organ segmentation
- Hybrid Task Cascade for Instance Segmentation
- Multi-stage Multi-recursive-input Fully Convolutional Networks for Neuronal Boundary Detection
- A multi-task U-net for segmentation with lazy labels
<br/>

*Person detection (July 22 2019)*
- CrowdHuman: A Benchmark for Detecting Human in a Crowd
- Center and Scale Prediction: A Box-free Approach for Object Detection
- Frustum PointNets for 3D Object Detection from RGB-D Data
<br/>

*Object detection (Aug 13 2019)*
- Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving
- DisNet: A novel method for distance estimation from monocular camera
- Stereo R-CNN based 3D Object Detection for Autonomous Driving

*Radar
- [Self-Supervised Occupancy Grid Learning From Sparse Radar for Autonomous Driving](https://www.groundai.com/project/self-supervised-occupancy-grid-learning-from-sparse-radar-for-autonomous-driving/1)
<br/>




### Updated
- Railroad semantic segmentation on high-resolution images (ITSC 2020)
- An Open Data Set for Rail Vehicle Positioning Experiments (ITSC 2020)
- RailNet: An Information Aggregation Network for Rail Track Segmentation
- RailNet: a Segmentation Network for Railroad Detection
- Deep Learning for Image and Point Cloud Fusion in Autonomous Driving: A Review
- https://github.com/QingyongHu/SoTA-Point-Cloud
- OpenPCDet Toolbox for LiDAR-based 3D Object Detection
  - https://github.com/open-mmlab/OpenPCDet
<br/>


