# Data Mining 2021
数据挖掘课程2021年作业

**姓名**：杨毅哲

**学号**：3120201088

## 作业一：数据探索性分析与数据预处理

### 1. 数据集选择

- [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews)：
  - 该数据集是关于葡萄酒评价的数据，共有三个数据文件:
    - winemag-data-130k-v2.csv：包含10列和130k行关于葡萄酒的评价
    - winemag-data_first150k.csv：包含10列和150k行关于葡萄酒的评价
    - winemag-data-130k-v2.json：保护6919个关于葡萄酒评价的节点
  - 本次数据挖掘试验选取的是winemag-data_first150k.csv数据
- [MLB Pitch Data 2015-2018](https://www.kaggle.com/pschale/mlb-pitch-data-20152018)
  - 该数据集是美国职业棒球大联盟的数据，共有五个数据文件：
    - atbats.csv：棒球打数数据文件
    - ejections.csv：棒球抛球数据文件
    - games.csv：棒球比赛数据文件
    - pitches.csv：棒球数据文件
    - player_name.csv：运动员数据文件
  - 本次数据挖掘试验选取所有的数据文件进行分析

### 2. 数据分析要求

#### 2.1 数据可视化与摘要

- 数据摘要
  - 标称属性，给出每个聚会的频数
  - 数值属性，给出5数概括以及缺失值的个数
- 数据可视化
  - 使用直方图、盒图等检查数据分布及离群点

#### 2.2 数据缺失的处理

观察数据集中缺失的数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理：

- 将缺失部分剔除
- 使用最高频率值来填补缺失值
- 通过属性的相关关系来填补缺失值
- 通过数据对象之间的相似性来填补缺失值

注意：在处理后，要可视化地对比新旧数据集

### 3. 数据分析报告

数据分析报告由Jupyter Notebook组织

**作业报告**：[DataMiningAssginment1.ipynb](./DataMiningAssginment1.ipynb)

