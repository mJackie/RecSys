推荐系统/计算广告/机器学习/CTR预估资料汇总
===
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md) ![Update](https://img.shields.io/badge/update-weekly-green.svg) ![Progress](https://img.shields.io/badge/progress-1003%20%2F%201003-ff69b4.svg) [![SayThanks](https://img.shields.io/badge/say-thanks-ff69f4.svg)](https://saythanks.io/to/kamyu104) ![Travis](https://travis-ci.org/kamyu104/LeetCode-Solutions.svg?branch=master)

**说明**：本仓库主要汇集推荐系统/计算广告/机器学习/CTR预估相关学习资料，欢迎一起补充更新👼

**持续更新中……**

# RoadMap
- [推荐系统](#推荐系统)
- [计算广告](#计算广告)
- [统计学习模型](#统计学习模型)
	- [技术文章](#技术文章)
	- [实践工具](#实践工具)
- [深度学习模型](#深度学习模型)
	- [技术文章](#技术文章)
	- [实践代码](#实践代码)
- [相关比赛](#相关比赛)
	- [Criteo Display Advertising Challenge](#CriteoDisplayAdvertisingChallenge)
	- [Avazu Click Through Rate Prediction](#AvazuClickThroughRatePrediction)
	- [2018 IJCAI 阿里妈妈搜索广告转化预测](#2018-IJCAI-阿里妈妈搜索广告转化预测)
	- [2018腾讯广告算法大赛](#2018腾讯广告算法大赛)
- [技术博客](#技术博客)

---

### 推荐系统
- [推荐系统实践-项亮](./resource/推荐系统实践-项亮.pdf)
- [亿级用户个性化品类推荐实战](https://gitbook.cn/books/5acc23b4f453ee79e417c729/index.html)

---

### 计算广告
- [互联网广告系统综述系列博文](https://blog.csdn.net/mytestmy/article/list)
- [计算广告学系列视屏-刘鹏](https://study.163.com/course/introduction.htm?courseId=321007#/courseDetail?tab=1)
- [计算广告学讲义-刘鹏](https://dirtysalt.github.io/html/computational-advertising.html)

---

### 统计学习模型
#### 技术文章
- [逻辑回归LR模型简介](https://tech.meituan.com/2015/05/08/intro-to-logistic-regression.html)
- [FFM讲解PPT](./resource/ffm.pdf)
- [深入FFM原理与实践](https://tech.meituan.com/2016/03/03/deep-understanding-of-ffm-principles-and-practices.html)
- [GBDT算法原理与系统设计简介](./resource/GBDT-wepon.pdf)

#### 实践工具
- [LightGBM](https://github.com/Microsoft/LightGBM)
- [XGBoost](https://github.com/dmlc/xgboost)
- [LIBFFM](https://github.com/guestwalk/libffm)
- [xLearn](https://github.com/aksnzhy/xlearn)

---

### 深度学习模型
#### 技术文章
- [深度学习如何应用在广告、推荐及搜索业务？](https://mp.weixin.qq.com/s/nboZ6p_l30L__FJNyz6Ohw)
- [深度学习在CTR预估中的应用](https://zhuanlan.zhihu.com/p/35484389)
- [深度学习在 CTR 中应用](http://www.mamicode.com/info-detail-1990002.html)
- [深度学习在美团点评推荐业务中实践](https://gitbook.cn/books/5aa0dd15cfbe2c144b71906d/index.html)
#### 实践代码
- [CTR预估算法之FM, FFM, DeepFM及实践](https://github.com/Johnson0722/CTR_Prediction)
- [推荐系统中使用ctr排序的dnn模型](https://github.com/nzc/dnn_ctr)

---

### 相关比赛
#### [CriteoDisplayAdvertisingChallenge](https://www.kaggle.com/c/criteo-display-ad-challenge)
- Rank1: [借鉴了Facebook的方案: GBDT 特征编码 + FFM](https://www.kaggle.com/c/criteo-display-ad-challenge/discussion/10555)
- Rank3: [Quadratic Feature Generation + FTRL 传统特征工程和 FTRL 线性模型的结合](https://www.kaggle.com/c/criteo-display-ad-challenge/discussion/10534)

#### [AvazuClickThroughRatePrediction](https://www.kaggle.com/c/avazu-ctr-prediction)
- Rank1: [Feature Engineering + FFM + Ensemble, 只基于 FFM 进行集成](https://www.kaggle.com/c/avazu-ctr-prediction/discussion/12608)
- Rank2: [Feature Engineering + GBDT 特征编码 + FFM + Blending](https://github.com/owenzhang/kaggle-avazu)

#### [2018 IJCAI 阿里妈妈搜索广告转化预测](https://tianchi.aliyun.com/competition/entrance/231647/introduction?spm=5176.12281957.1004.10.38b04c2aaROEf9)
- Rank1: [GBDT，用了嫁接技术处理样本分布不一致](https://github.com/plantsgo/ijcai-2018)
- Rank2: [GBDT单模型+大量特征工程](https://github.com/YouChouNoBB/ijcai-18-top2-single-mole-solution)

#### [2018腾讯广告算法大赛](https://algo.qq.com/)
- Rank3: https://github.com/DiligentPanda/Tencent_Ads_Algo_2018
- Rank6: https://github.com/nzc/tencent-contest

---

### 技术博客
- [美团技术点评](https://tech.meituan.com/)
- [火光摇曳](http://www.flickering.cn/)
- [推荐系统理论及实战](https://www.jianshu.com/nb/21403842)

### Todo
- 经典论文paper整理
- 与图像/NLP/知识图谱的结合
- 强化学习模型(Bid相关)


