---
layout: post
title: "机器学习算法"
date: 2018-09-02 
description: "机器学习进阶篇"
tag: 机器学习  

---     

### 机器学习算法  

####  1.**回归算法** （Regression Algorithm）

　　**原理：** 回归问题的学习等价于函数拟合：找到一条函数曲线使其很好的拟合已知点或函数，以很好地预测未知数据。对于一些给定的离散点，我们利用最小二乘法找到这些点到一条直线的**欧式距离**之和最小时的函数，这个过程就是线性回归。
  　**概念：**用已知样本对未知函数参数的估计，给出一个点集D，用一个函数去拟合这个点集，并且使得点集与拟合函数间的均方误差最小，如果这个函数曲线是一条直线，那就被称为线性回归，如果曲线是一条二次曲线，就被称为二次回归。
  　**例子：**一个例子：f(x,y,z,…)=ax+by+cz+…+…其中x，y，z是训练样本集中样本的各个特征(feature)，a，b，c是模型的未知参数，通过“回归”将这些特征拟合到最能解释这些特征的线性函数中去的过程就是回归。      
　　

#### 2.**基于实例的算法** （Instance-based Algorithm ）
　　**原理：** 基于实例的算法常常用来对决策问题建立模型，这样的模型常常先选取一批样本数据，然后根据某些近似性把新数据与样本数据进行比较。通过这种方式来寻找最佳的匹配。因此，基于实例的算法常常也被称为“赢家通吃”学习或者“基于记忆的学习”。
　　**算法：**常见的此类算法有　　
    (1)K-近邻算法（KNN）;
    (2)学习矢量量化（LVQ）;
    (3)自组织映射算法（SOM）。
    
　　**例子：** K-近邻算法(KNN) 。KNN算法属于监督学习算法，主要用于分类。存在一个样本数据集合，也称作训练集，并且训练集中的每个样本都存在标签。当输入一个未知标签的新数据时，将新数据的每个特征与训练集中的数据对应的特征进行比较，然后算法提取样本集中特征最相似数据（最近邻）的分类标签。
  
　　**KNN算法步骤:**　
> Step1 计算已知类别数据中的点到当前点之间的距离；
Step2 按照距离递增次序排序；
Step3 选取与当前点距离最小的k个点；
Step4 确定前k个点所在类别的出现频率；
Step5 返回前k个点出现频率最高的类别作为当前点的预测分类。

   **注意:**未完待续...(To be continuted.......)
<br>

     
转载请注明：[何爱平的博客](http://AndrewHeaiping.github.io) » [点击阅读原文](https://www.heaiping.cn/2016/07/MachineLearning_introduce/)