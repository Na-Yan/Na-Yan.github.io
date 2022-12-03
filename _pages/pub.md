---
layout: archive
permalink: /pub/
author_profile: true
title: "Publications"
---


## Improving Barely Supervised Learning by Discriminating Unlabeled Samples with Super-Class
[[PDF]](https://openreview.net/pdf?id=Nlsr4DepNt) [[Poster]](https://nips.cc/media/PosterPDFs/NeurIPS%202022/54238.png)

### Published in Neural Information Processing Systems (NeurIPS), 2022

**Abstract** In semi-supervised learning (SSL),  a common practice is to learn consistent information from unlabeled data and discriminative information from labeled data to ensure both the immutability and the separability of the classification model.  Existing SSL methods  suffer from failures in barely-supervised learning (BSL), where only one or two labels per class are available, as the insufficient labels cause the discriminative information being difficult or even infeasible to learn. To bridge this gap, we investigate a simple yet effective way to leverage unlabeled samples for discriminative learning, and propose a novel discriminative information learning module to benefit model training. Specifically, we formulate the learning objective of discriminative information at the super-class level and dynamically assign different classes into different super-classes based on  model performance improvement. On top of this on-the-fly process, we further propose a distribution-based loss to learn discriminative information by utilizing the similarity relationship between samples and super-classes. It encourages the  unlabeled samples to stay closer to the distribution of their corresponding super-class than those of others. Such a constraint is softer than the direct assignment of pseudo labels, while the latter could be very noisy in BSL. We compare our method with state-of-the-art SSL and BSL methods through extensive experiments on standard SSL benchmarks. Our method can achieve superior results, \eg, an average accuracy of 76.76% on CIFAR-10 with merely 1 label per class.


