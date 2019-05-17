
# Advertising

## Overview

### 计算广告CTR预估系列 1-9 

from公众号：机器学习荐货情报局

- [计算广告CTR预估系列(一)--DeepFM理论](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483673&idx=1&sn=256e57219c8d577c61f25221c346053c&chksm=fb77c157cc004841581591543041044f490825c59360dd485a4d005b0c3823feb0d0c39bf9e3&scene=21#wechat_redirect)

- [计算广告CTR预估系列(二)--DeepFM实践](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483677&idx=1&sn=5bf0ac27124f57553cc8c17aa48664c7&chksm=fb77c153cc0048451db16d3ad2a6a6a0c7a001e9277b4a53caa2dd45cc457dac724e9e31a8a8&scene=21#wechat_redirect)

- [计算广告CTR预估系列(三)--FFM理论与实践](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483685&idx=1&sn=36de5b8814c7a1ca5d5a19315b3f1ed1&chksm=fb77c16bcc00487d937ca5c10a0682feecd8a1bcd4bc9ddbb13f21ccd3b353439c8ee724ff14&scene=21#wechat_redirect)

- [计算广告CTR预估系列(四)--Wide&Deep理论与实践](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483689&idx=1&sn=c6e55677fe4ee1983e8f51fb61dffab5&chksm=fb77c167cc004871347a79fddb1c70d44f2b4bb54cbf09c3d1ecc5473ff8653802354d65bb8d&scene=21#wechat_redirect)

- [计算广告CTR预估系列(五)--阿里Deep Interest Network理论](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483704&idx=1&sn=2b80e3def93056e4afb39cc1e744d18a&chksm=fb77c176cc0048607a4f54c787aaf254fc8bd0e852c6c3cb4baa7546073f27e706244391b35e&scene=21#wechat_redirect)

- [计算广告CTR预估系列(六)--阿里Mixed Logistic Regression](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483707&idx=1&sn=5810c525e2880edb795543d5b8bd4aa2&chksm=fb77c175cc0048631a92201e5d4fffcf514f683540cf763a89626f99fc6bba66ac962fa3a07a&scene=21#wechat_redirect)

- [计算广告CTR预估系列(七)--Facebook经典模型LR+GBDT理论与实践](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483711&idx=1&sn=14e8d906d84de78b249510b33d423b89&chksm=fb77c171cc0048670169bda56327473f29b60c30187b67812261d13fc6518762f88611c61949&scene=21#wechat_redirect)

- [计算广告CTR预估系列(八)--PNN模型理论与实践](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483719&idx=1&sn=ab9b912145c94ef299bc8484372794e9&chksm=fb77c109cc00481f47664515bb4f1ef6fefbc598f88693888572aff5010d2637398a260e1e8a#rd)

- [计算广告CTR预估系列(九)--NFM模型理论与实践](https://mp.weixin.qq.com/s?__biz=MzU0NDgwNzIwMQ==&mid=2247483738&idx=1&sn=61334a86c12f027cf6964196b62b3e7e&chksm=fb77c114cc0048025b505eee6a9d48e178bc073a968d617bc945e2922cec0041456f11770ccd#rd)


## Classic


## Deep Learning

### 0. Overview


### 1. [Audience Expansion for Online Social Network Advertising - LinkedIn2016](https://www.kdd.org/kdd2016/papers/files/adf0483-liuA.pdf)

**Keywords**: Online Advertising; Audience Expansion; Lookalike Modeling

**Key Points**: 

### 2. [Practical Lessons from Predicting Clicks on Ads at Facebook - Facebook2014](http://quinonero.net/Publications/predicting-clicks-facebook.pdf)

**Keywords**: LR + GBDT

**Key Points**: 利用树模型(GBDT)组合特征的能力自动做特征组合，作为新的特征叠加到LR模型里再训练一个LR模型。


#### Article

- [Practical Lessons from Predicting Clicks on Ads at Facebook](<http://www.bubuko.com/infodetail-1902390.html>)


### 3. DIN - [Deep Interest Network for Click-Through Rate Prediction - Ali2018](https://arxiv.org/abs/1706.06978)

**Keywords**: CTR Prediction; Display Advertising; E-commerce; DIN; Attention Mechanism

**Key Points**: 引入了Attention Mechanism

#### Article

- [推荐系统中的注意力机制——阿里深度兴趣网络(DIN)](https://zhuanlan.zhihu.com/p/51623339)

- [计算广告CTR预估系列(五)--阿里Deep Interest Network理论](https://blog.csdn.net/u010352603/article/details/80590152)


#### 4. Mixed LR - [Learning Piece-wise Linear Models from Large Scale Data for Ad Click Prediction - Ali2017](https://arxiv.org/abs/1704.05194)

**Keywords**: Mixed LR; 

**Key Points**: 基于Mixed LR的CTR模型，核心思想是聚类LR

#### Article

- [计算广告CTR预估系列(六)–阿里Mixed Logistic Regression](https://blog.csdn.net/u010352603/article/details/80681239)