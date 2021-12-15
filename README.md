# Kaggle-House-Prices-
关于Kaggle入门竞赛House Prices 房价预测的比赛，0.12308分，660名，Top10%左右。

## **总结**
* 这是一篇关于Kaggle入门竞赛 **House Prices - Advanced Regression Techniques**的分享。通过探索性分析，数据预处理，特征工程以及模型构建综合分析房屋相关特征数据，通过机器学习建立并选择最优模型，对test数据集中房价进行预测。
* 基于Python机器学习库xgboost, sklearn参加Kaggle房价预测比赛实现实现回归，本项目使用多种模型结合，适当调参后得分在0.12308，660名，Top10%左右。
* 另有一版本调节SVR模型进行预测，最高0.11685分，128名（Top3%）尚在完善后续会更新。
* 开发环境:Python 3.86
<img src="/image/rank.png" align="center" width="900px"/>
<img src="/image/score_of_this_project.png" align="center" width="900px"/>

----------

## **项目下载**

```
git clone https://github.com/truman-zyx/Kaggle-House-Prices 
```

----------

## **比赛地址**
* 打开Kaggle官网进入Competitions搜索或者直接点击这里https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview

----------

## **比赛介绍**
<img src="/image/main_page.png" align="center" width="900px"/>

----------

## **数据集下载**
* 在官网项目界面即可下载数据集，共有四个，分别是提交示例，数据描述文件，训练集和测试集。
* 数据集说明：

|         File          | description                                            |
| :-------------------: | :----------------------------------------------------- |
| data_description.txt  | 描述train和test数据集中的房屋特征以及举例说明                |
| sample_submission.csv | 竞赛最终提交示例                                          |
|       train.csv       | 1460行房屋数据，包含79个特征，1个房屋ID数据以及一个房屋售价数据 |
|       test.csv        | 1459行房屋数据，包含79个特征以及1个房屋ID数据                |

----------

## 问题分析流程

<img src="/image/House Prices.png" align="center" width="900px"/>

----------

## 数据分析

<img src="/image/Data processing process.jpg" align="center" width="900px"/>

----------

## 项目架构
* 探索性分析
* 数据清洗
* 特征工程
* 建模及评价
* 整体方法

----------

## 模型得分
* 单个模型：

| Models |      Scores      |
| :----: | :--------------: |
| Ridge  |  115523+-0.0082  |
| Lasso  | 0.137979+-0.0053 |
|   RF   | 0.147239+-0.0088 |
|  GBR   | 0.135205+-0.0083 |
|  SVR   | 0.133621+-0.0122 |
| LinSVR | 0.120154+-0.0105 |
|  Ela   | 0.115902+-0.0064 |
|  SGD   | 0.144595+-0.0088 |
|  Bay   | 0.113206+-0.0068 |
|  Ker   | 0.114762+-0.0064 |
| Extra  | 0.140096+-0.0071 |
|  Xgb   | 0.148958+-0.0085 |


----------

如果有任何问题，请联系truman.yx.zuo@outlook.com
