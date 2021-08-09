---
abstract: Many machine learning algorithms have been developed under the assumption that data sets are already available in batch form. Yet in many application domains data is only available sequentially overtime via compute nodes in different geographic locations. In this paper, we consider the problem of learning a model when streaming data cannot be transferred to a single location in a timely fashion. In such cases, a distributed architecture for learning relying on a network of interconnected "local" nodes is required. We propose a distributed scheme in which every local node implements stochastic gradient updates based upon a local data stream. To ensure robust estimation, a network regularization penalty is used to maintain a measure of cohesion in the ensemble of models. We show the ensemble average approximates a stationary point and  characterize the degree to which individual models differ from the ensemble average. We compare the results with federated learning to conclude the proposed approach is more robust to heterogeneity in data streams (data rates and estimation quality). We illustrate the results with an application to image classification with a deep learning model based upon convolutional neural networks.

authors:
- Alfredo Garcia
- Luochao Wang
- Jeff Huang
- admin
date: "2021-03-01T00:00:00Z"
doi: ""
featured: false
image:
  caption: 'IEEE'
  focal_point: ""
  preview_only: false
links:
- name: IEEE Link
  url: https://ieeexplore.ieee.org/abstract/document/9219212?casa_token=B6bKb6ZaQsIAAAAA:4-mOIDzD-ktDsmdubgDMveptn2HRO6k5g7vvwguTsMh1vWAj7dUFVMBP_Eui8JYKeOjJcuhy/
projects: 
- Optimization Research
- IEEE
publication: '*IEEE Transactions on Control of Network Systems, 8*(1)'
publication_short: "IEEE"
publication_types:
- "2"
publishDate: "2021-03-01T00:00:00Z"

summary: IEEE Transactions on Control of Network Systems
tags:
- Optimization
- Distributed Networked Learning
- IEEE
title: Distributed Networked Real-Time Learning

---

