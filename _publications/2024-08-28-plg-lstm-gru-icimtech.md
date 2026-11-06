---
title: "Parallelization of LSTM-GRU Architectures for Multivariate Prediction of Stock Prices"
collection: publications
category: conferences
permalink: /publication/plg-lstm-gru-parallelization/
excerpt: "Anticipating stock market movements is challenging, as hasty prediction risks large financial losses."
date: 2024-08-28
venue: '2024 International Conference on Information Management and Technology (ICIMTech), IEEE, pp. 311-315'
paperurl: '/files/plg-lstm-gru-preprint.pdf'
citation: 'Tarigan, G. A.; Hermawan, E. S.; &amp; Girsang, A. S. (2024). &quot;Parallelization of LSTM-GRU Architectures for Multivariate Prediction of Stock Prices.&quot; <i>2024 International Conference on Information Management and Technology (ICIMTech)</i>, pp. 311-315.'
---

Anticipating stock market movements is challenging, as hasty prediction risks large financial losses. Stock price prediction is complex due to the high volatility and many influencing external factors. Recurrent Neural Network (RNN) models are made to learn time series data making it ideal for stock prediction based on records. Well-known RNN architectures for forecasting problems are Long-Short Term Memory (LSTM) and Gated Recurrent Unit (GRU). However, past studies only explored standalone models and have not generated convincing performance results. By integrating the efficiency of GRU to effectively handle shorter data sequences with LSTM's ability to capture long-term dependencies, our model aims to improve stock price forecasting accuracy by collaborating the strength between both architectures. The proposed model was used to forecast multivariate stock prices and evaluated using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE). We found that parallelization of LSTM-GRU offers better prediction, up to 9.1% improvement compared to sequential LSTM-GRU and Bidirectional LSTM (Bi-LSTM).

Published at the 2024 International Conference on Information Management and Technology (ICIMTech). This work parallelizes hybrid LSTM-GRU architectures for multivariate stock price prediction and benchmarks them against transformer-based comparators.

The IEEE version is available via [DOI: 10.1109/ICIMTech63123.2024.10780885](https://doi.org/10.1109/ICIMTech63123.2024.10780885). A free preprint is available for download.
