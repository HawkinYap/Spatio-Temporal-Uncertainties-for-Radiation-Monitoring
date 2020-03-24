# 城市级核辐射可视化监控软件

随着我国经济的不断发展，能源短缺和环境污染问题日益严重。作为一种高效、清洁、可持续发展的能源，核电日益成为我国能源发展的重要选择。但是，依靠核反应堆发电的核电站和其他发电站一样，也存在着安全问题。核电站泄漏事故给人类、自然带来的巨大危害使我们“谈核色变”，因此，在日常生活中对核辐射的常规检测非常重要。核辐射检测仪器（传感器）是核辐射检测的一种通用方式，本着覆盖面广、性能高的原则，市面上的核辐射传感器分为专业校准的静态传感器和车载的移动传感器。静态传感器精度高，价格昂贵，常部署在城市的关键地标或交通枢纽处；动态传感器活动范围广，精度较低，随车记录一定区域内的辐射变化情况。然而，两种传感器生产标准的差异不可避免地会造成时空数据的高度不确定性，甚至直接影响分析和应用结果的可靠性。有效的可视化手段可以通过精心设计的可视化视图和交互来帮助理解和分析复杂的不确定性，从而在向检测人员展示核辐射水平的同时展示地域和时空的核辐射不确定性，以便分析人员更好的对城市核辐射状况做出更精准的判断与决策。因此，需要一个基于时空的核辐射不确定性可视化系统来帮助城市更好的监管和控制核辐射水平，从而保障整个城市的安全。

本系统实现了一种城市级核辐射时空可视化监控的可视分析方法，该方法将时空可视化与不确定性可视化方法结合起来，在时空可视化中采用了辐射读数折线图和地理网格插值两种方法展示核辐射示数的时空信息，在不确定性可视化中设计了多层次信息树图、基于网格的不确定性框图、基于模糊度的不确定性面积图、基于不确定性数值运算的色带图，并提供了多种交互手段实现两种数据的联动分析、相互验证和取长补短。针对静态传感器地理检测范围的不确定和动态传感器示数不稳定的情况，将动静态传感器示数的时空显示、两者的不确定性区域与交互设计结合起来，相互佐证，共同决策。分析人员根据专业经验和从其它视图中获得的信息，以总控核辐射时间序列变化图，核辐射不确定性表征的示数地图以及多层次数图作为人机交互接口，调节不同时段的自动化时序数据聚类结果或选定特定传感器，地图界面根据调节内容显示相应的示数与不确定性运算结果。本系统还设计了一套新颖的不确定性量化指标，与动静态传感器读数的关键特征相对应，这些指标是在美国国家安全层次划分方法的基础上定义的，并用梯形模糊隶属函数进行度量，通过星型等级进行可视化展示，从而定量的展示传感器示数的不确定性情况，有助于分析人员了解不同传感器的多特征时变模式。

## 系统案例展示1
![image](https://github.com/HawkinYap/Spatio-Temporal-Uncertainties-for-Radiation-Monitoring/blob/master/assets/case1.jpg)
## 系统案例展示2
![image](https://github.com/HawkinYap/Spatio-Temporal-Uncertainties-for-Radiation-Monitoring/blob/master/assets/case2.jpg)
## 系统功能展示
![image](https://github.com/HawkinYap/Spatio-Temporal-Uncertainties-for-Radiation-Monitoring/blob/master/assets/case3.jpg)
## 系统视频介绍
![image](https://github.com/HawkinYap/Spatio-Temporal-Uncertainties-for-Radiation-Monitoring/blob/master/assets/video.gif)

 
