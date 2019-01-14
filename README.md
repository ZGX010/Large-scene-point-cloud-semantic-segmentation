# Large-scene-point-cloud-semantic-segmentation
---   
##  Updata Time:2019_01_14
**Number:** 29 <br>
**Name:**  Point Cloud Labeling using 3D Convolutional Neural Network <br>
**Publication category:**  <br>
**Publication Name:** ICPR <br>
**Issuing Time:**  2016_12  <br>
**Contribution:**  介绍了一种基于三维卷积神经网络的3D点云标签方案，3D-CNN
在3D网络的体素化，训练和测试期间，提出了有效处理大数据的解决方案<br>
**Difficulty:** 方法不需要先验知识，例如地面和/或建筑物的分割，预先计算的法线等等。一切都是基于
体素化数据，这是一种直接的表示。从另一种观点认为，我们的方法是一种端到端分割方法  <br>
**Result:** 汽车和飞机准确率高于95％，而建筑物，电线杆和电线的精度在80％到90％之间，树木的准确度略低于80％  <br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 28 <br>
**Name:**  面向对象的倾斜摄影测量点云分类方法 <br>
**Publication category:** 北大中文核心 <br>
**Publication Name:** 国土资源遥感  <br>
**Issuing Time:**  2018_06  <br>
**Contribution:**  提出了一种面向对象的倾斜摄影测量点云分类方法
首先!计算单点特征向量,然后!利用SLIC(算法将点云对应的影像分割成超像素!再根据点云和影像间的关系!将点云聚类成超体素对象!并计算每个对象的特征向量) 在此基础上!采用随机森林算法对超体素进行分类) 最后!根据语义信息对分类结果进行后处理获得最终的点云分类结果<br>
**Difficulty:** 需要挖掘更多更有效的特征来提高分类精度 <br>
**Result:** 总体分类精度分别达到91.2%和88.1%,比基于单点的分类方法分别提高了2.3%和8.2%  <br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 27 <br>
**Name:**  A shape-based segmentation method for mobile laser scanning point clouds <br>
**Publication category:** ScienceDirect <br>
**Publication Name:** ISPRS <br>
**Issuing Time:**  2015_09  <br>
**Contribution:**  提出基于形状的分割方法,所提出的方法首先计算每个点的最佳邻域尺寸以导出与其相关联的几何特征，然后使用支持向量机（SVM）根据几何特征对点云进行分类。其次，定义了一组规则来对分类点云进行分割，并提出了分段的相似性标准来克服过分割。最后，分段输出基于拓扑连接合并为有意义的几何抽象<br>
**Difficulty:** 城市场景的点云包含大量具有显着尺寸可变性，复杂和不完整结构以及孔洞或可变点密度的物体，这对移动激光点云的分割提出了巨大挑战 <br>
**Result:**  <br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 26 <br>
**Name:**  车载激光扫描数据中多类目标的层次化提取方法 <br>
**Publication category:**  EI <br>
**Publication Name:** 测绘学报 <br>
**Issuing Time:**  2015_09  <br>
**Contribution:**  发展了基于超级体素的点云分割方法
融合点云的几何、纹理和反射强度等多种特征进行分割和分类，提高了复杂场景中点云分割和目标提取的质量
<br>
**Difficulty:** 点云分割的结果依赖于超级体素分类的结果，当体素分类出错时，会导致错误的分割结果 <br>
**Result:** 提取出建筑物、地面、路灯、树木、电线杆、交通标志牌、汽车、围墙等多类目标，目标提取的总体精度为92.3% <br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 25 <br>
**Name:**  基于DBN的车载激光点云路侧多目标提取 <br>
**Publication category:**  EI <br>
**Publication Name:** 测绘学报 <br>
**Issuing Time:**  2018_12  <br>
**Contribution:**  总结了传统的点云分割方法和深度学习分割方法
介绍了DBN网络<br>
**Difficulty:** 仅考虑其整体形态轮廓特征,而没有兼顾目标对象自身点
云数据属性特征的差异 <br>
**Result:** 采用准确率，精度，召回率进行评价
行道树提取结果的准确率达97.31%,召回率达98.30%,精度达95.70%％<br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 24 <br>
**Name:**  车载LiDAR点云路灯提取方法 <br>
**Publication category:**  EI <br>
**Publication Name:** 测绘学报 <br>
**Issuing Time:**  2018_12  <br>
**Contribution:**  将传统点云提取方法分为：1 基于空间聚类的方法 2 基于几何特征的方法
3 基于超体元的方法 4 基于模板匹配的方法 四大类<br>
**Difficulty:**  <br>
**Result:**  <br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 23 <br>
**Name:** 三维激光扫描点云数据处理研究进展、挑战与趋势 <br>
**Publication category:** EI <br>
**Publication Name:** 测绘学报 <br>
**Issuing Time:** 2017_10 <br>
**Contribution:** 总结了三维激光扫描系统的现状
三维点云数据处理的关键进展
以及在测绘地理信息等领域的典型应用
并分析了三维点云数据处理面临的挑战,最后展望了三维激光扫描与点云处理的发展趋势 <br>
**Difficulty:**  <br>
**Result:** 传统分割方法：特征描述能力不足,分类和目标提取质量无法满足应用需求
深度学习方法：在三维点云场景的精细分类方面,还面临许多难题:海量三维数据集样本库的建立,适用于三维结构特征学习的神经网
络模型的构建及其在大场景三维数据解译中的应用 <br>
   <br>
   
##  Updata Time:2019_01_14
**Number:** 22 <br>
**Name:** VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection <br>
**Publication category:** IEEE <br>
**Publication Name:** Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition 2018 <br>
**Issuing Time:** 2018 <br>
**Contribution:** 提出了一种新的端到端的用于3D点云检测的深度学习框架：VoxelNet
提出了一种实施VoxelNet的有效方法这有利于稀疏点结构和体素网格上的高效并行处理 <br>
**Difficulty:** 扩展3D功能学习网络达到数量级更多的点和3D检测任务<br>
**Result:** 在KITTI数据集上car，准确率81.97，Pedestrian上，准确率为65.95，Cyclist上，准确率为61.17  <br>
   <br>
  
##  Updata Time:2019_01_12
**Number:** 21 <br>
**Name:** 三维点云数据分割研究现状<br>
**Publication category:**  <br>
**Publication Name:** 宜宾学院学报 <br>
**Issuing Time:** 2016_11_10 <br>
**Contribution:** 介绍三维点云数据分割的基本原理和特征，以及经典的点云数据集和测试平台，总结、对比现阶段各类点云分割算法的基本原理、特点和适用场景<br>
**Difficulty:** 现有算法的自适应能力差，大部分算法对异常点和噪声敏感，且效率也有待提升<br>
**Result:** 未来研究需充分利用点云数据的语境信息，进一步结合深度学习理论，从而提升点云分割效果  <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 20 <br>
**Name:** 三维点云场景数据获取及其场景理解关键技术综述 <br>
**Publication category:** 北大中文核心 <br>
**Publication Name:** 激光与光电子学进展 <br>
**Issuing Time:** 2018_09_14 <br>
**Contribution:** 总结了不同方式的点云获取方法，对不同的点云数据及相关数据库进行了对比分析
点云语义分割技术进行了对比分析与总结<br>
**Difficulty:** 三维场景理解关键技术存在的问题，尤其是针对具有颜色信息的激光点云的场景理解<br>
**Result:**    <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 19 <br>
**Name:** Large-scale Point Cloud Semantic Segmentation with Superpoint Graphs <br>
**Publication category:** IEEE <br>
**Publication Name:** CVPR 2018 <br>
**Issuing Time:** 2017_11_27 <br>
**Contribution:** 提出了一个深度学习框架来解决大规模点云的语义分割任务：SPGraph
目前在Semantic3D数据集的Benchmark中排名第一
介绍了超点图<br>
**Difficulty:** 数据的规模and缺乏类似于图像中的规则网格排列的清晰结构<br>
**Result:**  在Semantic3D数据集中，mIOU为0.762 ，OA为0.929  <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 18 <br>
**Name:** Multi-view Convolutional Neural Networks for 3D Shape Recognition <br>
**Publication category:** IEEE <br>
**Publication Name:** ICCV 2015<br>
**Issuing Time:** 2015 <br>
**Contribution:** 将3D点云投影到2D图像后作为卷积神经网络输入，创造了MVCNN（同类型snapnet）<br>
**Difficulty:** 这类方法会容易造成三维结构信息的丢失，而且投影角度的选取，同一角度的投影
对物体的表征能力也不同，对网络的泛化能力有一定的影响<br>
**Result:**  在Princeton ModelNet dataset 取得89.9% classification accuracy, and 70.1% mAP on retrieval <br>
 <br>

##  Updata Time:2019_01_12
**Number:** 17 <br>
**Name:** Deep Projective 3D Semantic Segmentation <br>
**Publication category:** <br>
**Publication Name:** CAIP2017<br>
**Issuing Time:** 2017_8_22 <br>
**Contribution:** 将点云组合到2D图像上，然后将这些图像用作到2D-CNN，提出DeePr3SS 调查了不同输入模态的影响，例如颜色，深度和表面法线<br>
**Difficulty:** 这类方法会容易造成三维结构信息的丢失，而且投影角度的选取，同一角度的投影
对物体的表征能力也不同，对网络的泛化能力有一定的影响<br>
**Result:**  在Semantic3D数据集中，mIOU为0.585，OA为0.889 <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 16 <br>
**Name:** VoxNet: A 3D Convolutional Neural Network for Real-Time Object Recognition <br>
**Publication category:** IEEE <br>
**Publication Name:** IROS 2015<br>
**Issuing Time:** 2015 <br>
**Contribution:** 卷积计算量非常大，网络中仅利用了点云的结构信息，没有考虑到点云的颜色
，强度等信息<br>
**Difficulty:** 这类方法会容易造成三维结构信息的丢失，而且投影角度的选取，同一角度的投影
对物体的表征能力也不同，对网络的泛化能力有一定的影响<br>
**Result:**   <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 15 <br>
**Name:** PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation  <br>
**Publication category:** IEEE <br>
**Publication Name:** CVPR 2017<br>
**Issuing Time:** 2017_07 <br>
**Contribution:** 提出了PointNet框架<br>
**Difficulty:** 对大规模点云还具有一定的局限性,不会捕获度量空间点引起的局部结构，限制了它识别细粒度模式的能力
无法处理局部特征<br>
**Result:**  在stanford 3D semantic parsing dataset上 mIoU为0.4771，OA为0.7862  <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 14 <br>
**Name:** PointNet++: Deep Hierarchical Feature Learning onPoint Sets in a Metric Space  <br>
**Publication category:**  <br>
**Publication Name:** AIPS 2017<br>
**Issuing Time:** 2017 <br>
**Contribution:** 针对PointNet局部特征信息进行了改进，推向多尺度，综合局部特征
提出了PointNet++
实现了鲁棒性和细节捕捉<br>
**Difficulty:** 如何生成点集的分区，以及如何通过本地特征学习器抽象点集或局部特征
点采样和分组策略没有揭示出入点云的空间分布<br>
**Result:**  Scannet labeling accuracy 是0.833  <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 13 <br>
**Name:** PointCNN: Convolution On X -Transformed Points  <br>
**Publication category:**  <br>
**Publication Name:** AIPS 2018<br>
**Issuing Time:** 2018 <br>
**Contribution:** 提出了PointCNN
通过对点云特性的分析，提出了一种基于点云中点学习到的X变化方法，对点云卷积处理
的性能有所提高<br>
**Difficulty:** X-transformations还有较大的改进空间，尤其是在排序方面<br>
**Result:**  在ShapeNet Parts数据集上，pIoU为0.8614，mpIoU为0.846
在S3DIS数据集上mIoU数据集为0.6539
在ScanNet数据集上的OA为0.851  <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 12 <br>
**Name:** SO-Net: Self-Organizing Network for Point Cloud Analysis  <br>
**Publication category:** IEEE <br>
**Publication Name:** CVPR 2018<br>
**Issuing Time:** 2018_03_12 <br>
**Contribution:** 提出了SO-net
提出了点云自编码器作为预训练在各种任务中提高网络性能
低计算成本<br>
**Difficulty:** 网络可能无法正确注释细粒度的细节<br>
**Result:**  在ShapeNetPart dataset数据集中，IoU为0.846,预训练IoU为0.849  <br>
  <br>

##  Updata Time:2019_01_12
**Number:** 11 <br>
**Name:** SEGCloud: Semantic Segmentation of 3D Point Clouds  <br>
**Publication category:**  arxiv <br>
**Publication Name:** Proceedings of the International Conference on 3D Vision<br>
**Issuing Time:** 2017_10_20 <br>
**Contribution:** 提出了SegCloud,获得3D点级的端到端框架<br>
**Difficulty:** <br>
**Result:**  在Semantic3D数据集上的mIOU为0.6310，mAcc为0.7308  <br>
  <br>

##  Updata Time:2019_01_11
**Number:** 10 <br>
**Name:** PointSIFT: A SIFT-like Network Module for 3D Point Cloud Semantic Segmentation  <br>
**Publication category:**  arxiv <br>
**Publication Name:**  <br>
**Issuing Time:** 2018_07_02 <br>
**Contribution:** 提出了一个PointSIFT框架编码不同方向的信息，从而有效的描述点云的形状 <br>
**Difficulty:** 有效的点云形状描述 <br>
**Result:** 在ScanNet数据集上准确率为86.2，mIoU为41.5
在S3DIS数据集上，准确率为88.72，mIoU为70.23<br>
  <br>
##  Updata Time:2019_01_11
**Number:** 09 <br>
**Name:** PointSIFT: Fast Semantic Segmentation of 3D Point Clouds using a Dense CRF with Learned Parameters  <br>
**Publication category:**  IEEE <br>
**Publication Name:**  ICRA <br>
**Issuing Time:** 2015_05_26 <br>
**Contribution:** 引入了一种3D点云的快速语言分割框架，基于随机森林分类器 <br>
**Difficulty:**  <br>
**Result:** 在NYU Depth datasets上处理数据速度是同类的两倍 <br>
  <br>
  
##  Updata Time:2019_01_11
**Number:** 08 <br>
**Name:** 3D All The Way:Semantic Segmentation of Urban Scenes From Start to End in 3D <br>
**Publication category:**  IEEE <br>
**Publication Name:**  ICRA 2015 <br>
**Issuing Time:** 2015 <br>
**Contribution:** 为3D城市模型提出了一种新的语义分割方法，从使用简单的3D功能，基于点的使用随机森林进行分类，并使用3D条件随机场平滑
速度快，能在几分钟内分析整条街道，3D标签可以与最先进的2D分类器的结果相结合，进一步提升业绩 ,完全以3D形式进行端到端的立面建模<br>
**Difficulty:** 市面上其他方法昂贵，此外，采集的3D数据不完整，包含了噪音，洞和杂乱<br>
**Result:** 在RueMonge2014数据集低精度数据上的IOU为52.09,时间为15min
高精度数据上的IOU为56.39，时间为76min<br>
  <br>

##  Updata Time:2019_01_11
**Number:** 07 <br>
**Name:** fast semantic segmentation of 3D point cloud with strongly varying density <br>
**Publication category:** ISPRS  <br>
**Publication Name:**  Remote Sensing and Spatial Information Sciences <br>
**Issuing Time:** 2016_04_01 <br>
**Contribution:**  描述了一种有效且高效的3D点云逐点语义分类方法。该方法可以处理非结构化和非均匀点云
它具有计算效率，可以在几分钟内处理具有数百万个点的点云<br>
**Difficulty:** The core of our method is an efficient strategy to construct approximate multi-scale neighborhoods in
3D point data <br>
**Result:** For Paris-Rue-Cassette and Paris-Rue-Madame the proposedmethod reaches 
overall classification accuracies of 95-98% at a mean class recall 93-99%  <br>
  <br>
  
##  Updata Time:2019_01_11
**Number:** 06 <br>
**Name:** 基于多尺度特征和 PointNet 的 LiDAR 点云地物分类方法 <br>
**Publication category:** 北大中文核心  <br>
**Publication Name:**  激光与光电子学进展 <br>
**Issuing Time:** 2018_10_07 <br>
**Contribution:**  针对 LiDAR 点云数据中复杂场景下地物分类问题，本文提出了一种基于多尺度特征和 PointNet 的
深度神经网络模型，对 PointNet 提取局部特征能力进行改进，实现 LiDAR 点云中复杂场景下的自动分类 <br>
**Difficulty:** 对PointNet提取局部特征能力进行了改进 <br>
**Result:** 在Semantic3 Ddataset数据集上mIOU为67.4，snapnet为59.1
在Vaihingen在城市数据集上mIOU为34.9,PointNe为32.0 <br>
  <br>
  
##  Updata Time:2019_01_11
**Number:** 05 <br>
**Name:**  PU-Net: Point Cloud Upsampling Network<br>
**Publication category:** IEEE  <br>
**Publication Name:** CVPR 2018  <br>
**Issuing Time:**  2018_01_21<br>
**Contribution:**  提出了一个数据驱动下的点云上采样技术<br>
**Difficulty:** 数据的稀疏性和不规则性 <br>
**Result:**   <br>
  <br>
  
 ##  Updata Time:2019_01_11
**Number:** 04 <br>
**Name:**  GSPN: Generative Shape Proposal Network for 3D Instance Segmentation in Point Cloud <br>
**Publication category:** arXiv   <br>
**Publication Name:**   <br>
**Issuing Time:** 2018_12_08<br>
**Contribution:** propose a Generative Shape Proposal Network to tackle 3D object proposal 
following an analysis-bysynthesis strategy 
基于区域的PointNe提出灵活的3D实例细分框架 <br>
**Difficulty:** 在传感器噪声较大和数据不完整的情况下，在杂乱的场景中具有各种比例的对象类别范围， 需要建立
对广义的语义和客体的理解 <br>
**Result:** 在ScanNet数据集上mean为30.6 <br>
  <br>
  
##  Updata Time:2019_01_11
**Number:** 03 <br>
**Name:** Dynamic Graph CNN for Learning on Point Clouds <br>
**Publication category:**  arXiv <br>
**Publication Name:**  <br>
**Issuing Time:** 2018_01_24 <br>
**Contribution:** 我们提出了一种新的点云操作，EdgeConv,
能更好地捕捉局部几何特征 <br>
**Difficulty:** 几何特征对3D识别任务的重要性 <br>
**Result:**  在ShapeNet part dataset mIOU为85.1
在S3DIS数据集上，mIOU为56.1<br>
  <br>
  
##  Updata Time:2019_01_11
**Number:** 02 <br>
**Name:** Spherical Convolutional Neural Network for 3D Point Clouds <br>
**Publication category:**  arXiv <br>
**Publication Name:**  <br>
**Issuing Time:** 2018_05 <br>
**Contribution:** 提出了一种利用球形的三维点云处理神经网络卷积核和空间的八叉树分割 <br>
**Difficulty:**  处理不规则点云上具有优势，直接实施在点云上，而不是算子<br>
**Result:** 在ModelNet10数据集上，为93.2
在ModelNet40数据集上，为85.2 <br>
  <br>

##  Updata Time:2019_01_11
**Number:** 01 <br>
**Name:** Dynamic Edge-Conditioned Filters in Convolutional Neural Networks on Graphs <br>
**Publication category:**  IEEE <br>
**Publication Name:**  CVPR <br>
**Issuing Time:** 2017_07_21 <br>
**Contribution:** formulate a convolution-like operation on graph signals performed in the spatial domain where filter
weights are conditioned on edge labels (discrete or continuous) and dynamically generated for each specific input sample
第一个在点云分类上应用图形卷积 <br>
**Difficulty:** a generalization of CNNs from grids to general graphs is not straightforward  <br>
**Result:** 在ModelNet10数据集上Mean class accuracy为89.3<br>
  <br>
##  Updata Time:2019_01_11
**Name:** Large-scene-point-cloud-semantic-segmentation by CNN <br>
**Publication category:** SCI <br>
**Publication Name:** computer <br>
**Issuing Time:** 2012_2_3 <br>
**Contribution:** Find a new CNNnet <br>
**Difficulty:**  <br>
**Result:** on the dataset that Kitti have 0.4mIoU    <br>
**Link** https://github.com/ZGX010/Signage-object-detection/blob/master/articles/Conference%20abstracts_English/%E4%BC%9A%E8%AE%AECVPR_2016_%E9%87%8E%E5%A4%96%E4%BA%A4%E9%80%9A%E6%A0%87%E5%BF%97%E6%A3%80%E6%B5%8B%E4%B8%8E%E5%88%86%E7%B1%BB.pdf <br>
**Thumbnail:** <br> 
<div align=center><img width="150" height="150" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>  <br>
  <br>

**Name:**  Large-scene-point-cloud-semantic-segmentation by CNN <br>
**Publication category:** SCI <br>
**Publication Name:** computer <br>
**Issuing Time:** 2012_2_3 <br>
**Contribution:** Find a new CNNnet <br>
**Difficulty:**  <br>
**Result:** on the dataset that cityspaces have 0.4mIoU    <br>
  <br>
