[我的博客](https://www.jianshu.com/u/4c4382e7b85f)

### 项目概述

该项目整理了 (以及分析和可视化) 的数据集是推特用户 @dog_rates 的档案, 推特昵称为 WeRateDogs。WeRateDogs 是一个推特主，他以诙谐幽默的方式对人们的宠物狗评分。这些评分通常以 10 作为分母。但是分子则一般大于 10：11/10、12/10、13/10 等等。为什么会有这样的评分？因为 "They're good dogs Brent." WeRateDogs 拥有四百多万关注者，曾受到国际媒体的报道。

WeRateDogs 下载了他们的推特档案，并通过电子邮件发送给优达学城，专门为本项目使用。这个档案是基本的推特数据（推特 ID、时间戳、推特文本等），包含了截止到 2017 年 4 月 1 日的 5000 多条推特。

WeRateDogs banner
图片来自 波士顿杂志*
我们需要什么软件？
使用这里使用了Jupyter Notebook workspace。
本项目来自优达学城课堂。

如果想在优达学城课堂以外操作，你需要满足以下软件要求：

你需要在电脑上用 Jupyter Notebook 操作。。
需要安装下列软件包（即 Python 库）。你可以通过 conda 或 pip 安装这些库。
pandas
numpy
requests
tweepy
json

### 数据结构
以该表格中的最后一行数据来理解各列数据：

- tweet_id 是推特链接的最后一部分，位于 "status/" 后面 → https://twitter.com/dog_rates/status/889531135344209921
- jpg_url 是预测的图像资源链接
- img_num 最可信的预测结果对应的图像编号 → 1 推特中的第一张图片
- p1 是算法对推特中图片的一号预测 → 金毛犬
- p1_conf 是算法的一号预测的可信度 → 95%
- p1_dog 是一号预测该图片是否属于“狗”（有可能是其他物种，比如熊、马等） → True 真
- p2 是算法对推特中图片预测的第二种可能性 → 拉布拉多犬
- p2_conf 是算法的二号预测的可信度 → 1%
- p2_dog 是二号预测该图片是否属于“狗” → True 真
- 以此类推...

### 项目细节
该项目完成以下内容：

#### 数据整理，其中包括：
- 收集数据
- 评估数据
- 清洗数据
#### 对清洗过的数据进行储存、分析和可视化

[我的博客](https://www.jianshu.com/u/4c4382e7b85f)
