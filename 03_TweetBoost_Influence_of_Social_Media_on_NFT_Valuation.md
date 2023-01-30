# TweetBoost: Influence of Social Media on NFT Valuation

**这篇文章是我看到的第一篇社交属性体现nft价值的文章，利用twitter中相关数据进行机器学习，能给出很多扩展研究方向。**

## 第一遍

从题目中就能看到，文章探讨的是社交媒体对NFT估值的影响。

在本文中，我们旨在回答以下研究问题：
RQ1：Twitter上的用户活动与OpenSea上的价格之间有什么关系？
RQ2：我们可以使用从Twitter和OpenSea获得的信号来预测NFT值吗；并确定哪些特征对预测影响最大？

主要贡献有：

1. 公开了一个连接Twitter和OpenSea（最大的NFT市场）的数据集，获取社交媒体概况和相关NFT资产，数据集目前状态良好（2023-01-30）
https://drive.google.com/file/d/1PxkIyyD3O3vwthb4axqZUWbjdXgkXBA7/view

2. 我们使用OpenSea和Twitter中的一些特征（如点赞，评论数）以及NFT图像本身构建有序分类模型来预测NFT资产价值。
表现最好的模型由Twitter和OpenSea的特征共同组成，在5级分类设置中实现了69.5%的准确率。

3. 我们表明Twitter和OpenSea的特征都会影响模型输出。
相比之下，图像特征的预测能力是有限的。这表明品牌和元数据（Twitter和OpenSea的特征）对价值的影响比NFT产品本身（图像功能）更强。
