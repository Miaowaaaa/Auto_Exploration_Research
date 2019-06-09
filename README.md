# Autonomous Exploration
This is a research of Robot Autonomouse Exploration 

## 总结
- 总体上看，自动探索目前研究的主流还是基于frontier的自动探索，研究热点在如何合理的规划探索的策略使得能够建出更完整的地图，花费更短的时间，行走更短的距离，耗费更少的能量。基于快速随机探索树（Rapidly Random-exploration Tree）的方法近些年被多次引用。
- 实验评价方式上，目前没有看到有文章中提起公开的地图数据集。都是在不同面积的模拟地图中进行测试和对比，并衡量探索区域完整度，时间消耗，行走距离这些指标进行对比。
对比的方法多是与不同的frontier探索策略进行对比。
- 基于信息理论的方法在17年，18年相对与frontier较少；
- 增强学习，对设备计算性能要求更高一些，