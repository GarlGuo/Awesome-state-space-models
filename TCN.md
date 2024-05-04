1. Biased Temporal Convolution Graph Network for Time Series Forecasting with Missing Values (https://openreview.net/forum?id=O9nZCwdGcG)

    Multivariate time series forecasting plays an important role in various applications ranging from meteorology study, traffic management to economics planning. In the past decades, many efforts have been made toward accurate and reliable forecasting methods development under the assumption of intact input data. However, the time series data from real-world scenarios is often partially observed due to device malfunction or costly data acquisition, which can seriously impede the performance of the existing approaches. A naive employment of imputation methods unavoidably involves error accumulation and leads to suboptimal solutions. Motivated by this, we propose a Biased Temporal Convolution Graph Network that jointly captures the temporal dependencies and spatial structure. In particular, we inject bias into the two carefully developed modules, the Multi-Scale Instance PartialTCN and Biased GCN, to account for missing patterns. The experimental results show that our proposed model is able to achieve up to % improvements over the existing methods on five real-world benchmark datasets. Our code is available at: https://github.com/chenxiaodanhit/BiTGraph.

    [GitHub](https://github.com/chenxiaodanhit/BiTGraph)



2. ModernTCN: A Modern Pure Convolution Structure for General Time Series Analysis (https://openreview.net/forum?id=vpJMJerXHU)

    Recently, Transformer-based and MLP-based models have emerged rapidly and won dominance in time series analysis. In contrast, convolution is losing steam in time series tasks nowadays for inferior performance. This paper studies the open question of how to better use convolution in time series analysis and makes efforts to bring convolution back to the arena of time series analysis. To this end, we modernize the traditional TCN and conduct time series related modifications to make it more suitable for time series tasks. As the outcome, we propose ModernTCN and successfully solve this open question through a seldom-explored way in time series community. As a pure convolution structure, ModernTCN still achieves the consistent state-of-the-art performance on five mainstream time series analysis tasks while maintaining the efficiency advantage of convolution-based models, therefore providing a better balance of efficiency and performance than state-of-the-art Transformer-based and MLP-based models. Our study further reveals that, compared with previous convolution-based models, our ModernTCN has much larger effective receptive fields (ERFs), therefore can better unleash the potential of convolution in time series analysis. Code is available at this repository: https://github.com/luodhhh/ModernTCN.

