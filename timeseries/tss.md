Time Series Forecasting With Deep Learning: A Survey BY Bryan Lim 1 and Stefan Zohren 
主要关注seq2seq架构，基本还是ar的思路。但是这些架构和混合架构都不能处理实际场景中的乱序时间序列和缺失，需要对乱序和缺失稳健的模型。其他需要关注的点有[可解释性](https://christophm.github.io/interpretable-ml-book/index.html)的ts和ts上的因果推断。
 
Trend analysis of climate time series: A review of methods
气候时间序列使用的方法，包括线性模型，非线性模型，非参回归模型。关注不确定性判别。

High-performance medicine: the convergence of human and artificial intelligence
人工智能医疗和药物设计。算法，场景，数据，提升健康产业效率。

Probabilistic Demand Forecasting at Scale
用spark搭建大规模时间序列概率预测架构

Volatility Forecasting. National
Bureau of Economic Research; 2005. 11188
 波动率预测用garch。

Recurrent Neural Filters: Learning Independent Bayesian Filtering Steps for Time Series Prediction
用贝叶斯滤波构造递归变分自编码器对装填空间转移概率建模。关注点，在时间步上传播的贝叶斯网络。



Deep Factors for Forecasting
假设每个时间步由全局因子和随机因子决定，混合效应模型加动态因子模型

Bayesian Filtering and Smoothing
很多滤波



Enhancing Time-Series Momentum Strategies Using Deep Neural Networks
用lstm在期货合约上做趋势和仓位预测


 Causal Interpretability for Machine Learning –Problems, Methods and Evaluation
机器学习的因果解释
先给了因果推断的定义分别是是结构模型，贝叶斯网络，和平均因果效应。三种因果解释方法，效果最好的是反事实推理。得到因果解释的四种方法，基于模型，反事实推理，因果和公平性，因果和数据

Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead
so on...

The M4 forecasting competition – A practitioner’s view
so practical...

Estimating Counterfactual Treatment Outcomes over Time Through Adversarially Balanced Representations
反事实循环架构预测治疗效果


总结：ts的表示方法，架构，因果推断（贝叶斯网络），泛函，测度。