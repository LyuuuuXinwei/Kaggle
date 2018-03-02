### Kaggle Corporación Favorita 商品销量预测比赛
竞赛链接：https://www.kaggle.com/c/favorita-grocery-sales-forecasting  

完整文档.pdf详细描述了整个竞赛的分析解决方案

目录如下：  
一．	赛题与数据介绍	1  
1.1赛题及背景	1  
1.2数据	2  
二．	我的解决方案概述	5  
2.1时间序列问题的整体解决方案	5  
2.2我的解决方案	6  
三．	数据探索	6  
3.1 商品销量整体分布	6  
3.2目标预测商品样本	7  
3.3 总体销量的时序形态	8  
3.4不同条目的销量变化模式	8  
四．	特征工程	9  
4.1历史销量统计量特征	9  
4.2为以上1, 3, 7, 14, 28, 60, 140天内的平均值构造差分	9  
4.3星期特征	9  
4.4历史移动窗口平均	9  
4.5 促销特征	10  
4.6类别特征	10  
五．	训练集验证集的选取	10  
5.1训练集的选取	10  
5.2验证集的选取	10  
六．	模型的设计	10  
6.1 lightGBM	10  
6.2 神经网络NN模型	10  
6.3其他尝试	10  
七．	引申学习	11  

### 文件结构  
data文件夹存放了原始数据的截图  
data exploring文件夹记录了分析过程  
my script为最后的解决方案  
top solution文件夹存放了优秀的解决方案  
