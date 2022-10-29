---
title: "Generalization to Unseen Viewpoint Images of Objects via Alleviated Pose Attentive Capsule Agreement"
collection: publications
permalink: /publication/2022-09-28-pose-attentive-caps-agreement-number-12
excerpt: ''
date: 2022-09-28
venue: 'Neural Computing and Applications'
paperurl: ''
citation: 'Özcan, B., Kınlı, F. & Kıraç, F. Generalization to unseen viewpoint images of objects via alleviated pose attentive capsule agreement. Neural Comput & Applic (2022). https://doi.org/10.1007/s00521-022-07900-3'
---

## Abstract
Despite their achievements in object recognition, Convolutional Neural Networks (CNNs) particularly fail to generalize to unseen viewpoints of a learned object even with substantial samples. On the other hand, recently emerged capsule networks outperform CNNs in novel viewpoint generalization tasks even with significantly fewer parameters. Capsule networks group the neuron activations for representing higher level attributes and their interactions for achieving equivariance to visual transformations. However, capsule networks have a high computational cost for learning the interactions of capsules in consecutive layers via the, so called, routing algorithm. To address these issues, we propose a novel routing algorithm, Alleviated Pose Attentive Capsule Agreement (ALPACA) which is tailored for capsules that contain pose, feature and existence probability information together to enhance novel viewpoint generalization of capsules on 2D images. For this purpose, we have created a Novel ViewPoint Dataset (NVPD) a viewpoint-controlled texture-free dataset that has 8 different setups where training and test samples are formed by different viewpoints. In addition to NVPD, we have conducted experiments on iLab2M dataset where the dataset is split in terms of the object instances. Experimental results show that ALPACA outperforms its capsule network counterparts and state-of-the-art CNNs on iLab2M and NVPD datasets. Moreover, ALPACA is 10 times faster when compared to routing-based capsule networks. It also outperforms attention-based routing algorithms of the domain while keeping the inference and training times comparable. Lastly, our code, the NVPD dataset, test setups, and implemented models are freely available at https://github.com/Boazrciasn/ALPACA.


[Paper][alpaca] |
[Code](https://github.com/Boazrciasn/ALPACA) 


[alpaca]: https://link.springer.com/article/10.1007/s00521-022-07900-3?error=cookies_not_supported&code=3a5ab1c3-ded3-4157-a0af-2dc76c936363

