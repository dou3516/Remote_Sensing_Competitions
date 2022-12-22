# Remote Sensing Competitions

📣:
🔥🔥🔥持续更新中🔥🔥🔥

# ⚡ 概述
近年来遥感影像智能处理比赛逐渐增多，既有周期性比赛，也有相关单位、企业主办的专题比赛，或周期性综合比赛中的专题赛道。
典型的周期性比赛如下：
| 赛事名称 | 主办方 | 官网链接 | 备注 |
|:--|:--|:--|:--|
| 遥感影像智能处理算法大赛 | 基金委/武大 | [rsipac](http://rsipac.whu.edu.cn/) | 2022年正常举行 |
| 天智杯人工智能挑战赛 | 航天系统装备部 | [tianzhibei](https://www.tianzhibei.org.cn/) | 2021年线下赛延期至今(2022) |
| 国际高分遥感图像解译大赛 | 高分办/中国科学院空天信息创新研究院 | [gaofen-challenge](https://www.gaofen-challenge.com/challenge)| 2022年度比赛未开展 |
| spacenet challenges | spacenet | [spacenet](https://spacenet.ai/challenges/) | SN7 is a NeurIPS 2020 Competition, now is SN8 |
| Data Fusion Contest (DFC) | IEEE | [DFC2022](https://76.223.36.25/competitions/data-fusion-contest-2022-dfc2022) |  |
| isprs benchmarks| ISPRS | [isprs benchmarks](https://www.isprs.org/education/benchmarks.aspx) | 提供各类摄影测量与遥感领域的测试基准 |

典型的专题比赛如下：
| 赛事名称 | 主办方 | 官网链接 | 备注 |
|:--|:--|:--|:--|
| 火箭军“智箭·火眼”人工智能挑战赛 | 火箭军装备部 | [“智箭·火眼”](https://www.yuanwangfangwugfw.com/hjjtzs) | 2020年，官网已下线，[推文链接](https://mp.weixin.qq.com/s/PTkPW0i8q05h0LUo1cp0Qg) |
| 2020年全国人工智能大赛“华为・昇腾杯” AI+遥感影像赛道 | 深圳市人民政府 | [2020NAIC](https://naic.pcl.ac.cn/landingpage/2020/index.html) [遥感赛道](https://naic.pcl.ac.cn/contest/6/track/24) | 官网可以打开，遥感赛道暂无法打开 |
| 2022数字中国创新大赛卫星应用赛题——海上船舶智能检测 | 数字中国建设峰会组委会 | [海上船舶检测赛道](https://www.dcic-china.com/competitions/10022) | 比赛数据存在部分为已开源数据 |
| 2020数字中国创新大赛应用赛1：建筑智能普查 | 数字中国建设峰会组委会 | [建筑智能普查](https://tianchi.aliyun.com/competition/entrance/231767/introduction) |  |
| 商汤科技 2020人工智能遥感解译大赛 | 商汤科技 | [senseearth](https://rs.sensetime.com/) | 官网已下线比赛信息 |
| CCF大数据与计算智能大赛-2020遥感影像地块分割赛道 | CCF | [2020遥感地块分割](https://www.datafountain.cn/competitions/475) |  |
|  |  |  |  |
|  |  |  |  |

# 📚 竞赛：按年度整理
以竞赛开始时间倒序。

## 2023
- **[[2023.1.3] 2023 IEEE GRSS Data Fusion Contest: Large-Scale Fine-Grained Building Classification for Semantic Urban Reconstruction](https://www.grss-ieee.org/technical-committees/image-analysis-and-data-fusion/?tab=data-fusion-contest)**<br>
**网站**： [竞赛网站](https://www.grss-ieee.org/technical-committees/image-analysis-and-data-fusion/?tab=data-fusion-contest) [中文介绍](https://mp.weixin.qq.com/s/2x3KaAhMS4okILMQ9-rJAg)<br>
**时间**：202.1.3 - 2022.5.22<br>
  - **赛道一：建筑物实例分割与屋顶细粒度分类**<br>
  **任务类型**：多模态实例分割<br>
  **简介**：该赛道旨在从高分辨率光学和SAR卫星图像中实现建筑物的实例分割与屋顶细粒度分类，探究光学和SAR数据的融合对建筑物提取效能的影响。<br>
   - **赛道二：面向多任务学习的城市建筑物提取与高度估计**<br>
  **任务类型**：多模态实例分割、高度估计<br>
  **简介**：该赛道旨在从高分辨率光学和SAR卫星图像中实现建筑物的提取与高度估计，探究多任务联合学习间的特征共享与信息互补机制。真值数据包括建筑物提取信息与nDSMs信息。<br>
  
## 2022
- **[[2022.11.17] 国家电网有限公司2022年人工智能竞赛公开赛-设备赛题-卫星遥感中输电杆塔和输电通道环境隐患目标智能提取](https://aistudio.baidu.com/aistudio/competition/detail/616/0/task-definition)**<br>
**网站**：[卫星遥感中输电杆塔和输电通道环境隐患目标智能提取](https://aistudio.baidu.com/aistudio/competition/detail/616/0/task-definition)<br>
**时间**：2022.11.17 - 2022.12.05<br>
**任务类型**：目标检测、语义分割<br>
**限制**：使用PaddlePaddle框架<br>
**简介**：<br>
针对输电线路的卫星遥感图像数据，采用图像识别、目标检测、语义分割等人工智能技术，对输电线路卫星遥感影像中输电杆塔本体以及水体、树木、建筑、易漂浮物等输电通道环境隐患进行检测辨识。预计初赛阶段针对输电杆塔（400项）、输电通道环境隐患目标（800项）发布训练样本1200项，随机选取测试样本300项（不公开），分别用于算法模型训练和模型性能测试；预计决赛阶段针对输电杆塔（800项）、输电通道环境隐患目标（1600项）发布训练样本2400项，随机选取测试样本600项（不公开），分别用于算法模型训练和模型性能测试。输电杆塔通过计算平均精确率、漏检率、误检率、平均计算时间等指标进行评测；输电通道环境隐患通过计算像素准确率与类别平均像素准确率等指标进行评测。<br>

- **[[2022.8.20] 2022遥感影像智能处理算法大赛](http://rsipac.whu.edu.cn/)**<br>
**网站**：[ 2022遥感影像智能处理算法大赛](http://rsipac.whu.edu.cn/)<br>
**时间**：2022.8.20 - 2022.11.--<br>
  - **赛道一：道路提取和交叉口识别**:<br>
  **任务类型**：目标检测、语义分割<br>
  **限制**：复赛使用华为硬件<br>
  **简介**：<br>
  基于遥感影像的道路提取对于自动驾驶、地图构建等应用具有重要意义。而现有道路提取方法多关注于道路像素级别的分割，而对于交叉口的识别关注较少，同时交叉口的识别定位对于更精细的道路拓扑构建和连通性信息判别就有重要意义。本赛道希望遴选出高效高精度的算法模型，同时识别出道路的分割掩膜和交叉口区域的定位。<br>
  - **赛道二：遥感影像变化检测**:<br>
  **任务类型**：变化检测<br>
  **限制**：无<br>
  **简介**：<br>
  变化检测对“耕地红线”、土地利用监管等应用具有重要意义。利用多时相遥感数据，采用多种图像处理和模式识别方法提取变化信息，并定量分析和确定地表变化的特征与过程，便是遥感变化检测的本质。传统遥感行业基于人工两期影像标注从而判别地物时相变化的方法受限于效率低、成本高等问题，难以满足实际应用需求，本赛道希望遴选出高效的遥感图像变化检测算法模型，对图像中的变化图斑信息进行高效识别，提高空间信息网络建设中遥感图像快速变化识别能力。变化检测赛道力求对通过前后两时相的遥感影像，提取出地物发生变化的斑块。选手使用主办方提供的两个时相的遥感图像进行变化判别处理，主办方依据评分标准对结果进行综合评价。依据所述地物变化标准，以耕地-建筑/动土的对象级变化检测为目标。<br>
  - **赛道三：遥感影像语义分割**:<br>
  **任务类型**：语义分割<br>
  **限制**：无<br>
  **简介**：<br>
  对高分辨率光学遥感图像中各类地物光谱信息和空间信息进行分析，将图像中具有语义信息的各个像元分别赋予语义类别标签；以包含典型土地利用分类的光学遥感图像为处理对象，选手使用主办方提供的遥感图像进行土地利用类型语义分割处理，主办方依据评分标准对结果进行综合评价。依据现有的遥感地物分类要求，结合现有的地物分类实际需求，参照地理国情监测、“三调”等既有地物分类标准，依据遥感地物“所见即所得”原则，设计地物要素分类体系，共涉及一级大类8种，二级子类17种。<br>

- **[[2022.06.04] SN8: Flood Detection Challenge Using Multiclass Segmentation](https://spacenet.ai/sn8-challenge/)**<br>
**网站**：[SN8 on topcoder](https://www.topcoder.com/challenges/a6c49990-e4a9-4e90-a731-4cc6502e6beb)<br>
**时间**：2022.06.04 - 2022.08.31<br>
**任务类型**：语义分割、变化检测<br>
**简介**：<br>
SpaceNet 8 aims to answer these questions:<br>
How have algorithms that extract buildings and roads improved since SpaceNet was launched, and how can top algorithms from previous challenges be leveraged? <br>
What is the impact on performance for a multiclass feature extraction challenge—i.e., buildings and roads? <br>
How accurately can roads obstructed by flood waters be characterized from pre-event road detections and post-event satellite imagery? <br>

## 2021

## 2020
