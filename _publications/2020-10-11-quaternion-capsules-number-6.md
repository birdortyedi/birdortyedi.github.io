---
title: "Quaternion Capsule Networks"
collection: publications
permalink: /publication/2020-10-11-quaternion-capsules-number-6
excerpt: ''
date: 2020-10-11
venue: '25th International Conference on Pattern Recognition, ICPR2020'
paperurl: ''
citation: 'Özcan, B., Kınlı, F. & Kıraç, F. (2020). Quaternion Capsule Networks. arXiv preprint arXiv:2007.04389.'
---

## Abstract
Capsules are grouping of neurons that allow to represent sophisticated information of a visual entity such as pose and features. In the view of this property, Capsule Networks outperform CNNs in challenging tasks like object recognition in unseen viewpoints, and this is achieved by learning the transformations between the object and its parts with the help of high dimensional representation of pose information. In this paper, we present Quaternion Capsules (QCN) where pose information of capsules and their transformations are represented by quaternions. Quaternions are immune to the gimbal lock, have straightforward regularization of the rotation representation for capsules, and require less number of parameters than matrices. The experimental results show that QCNs generalize better to novel viewpoints with fewer parameters, and also achieve on-par or better performances with the state-of-the-art Capsule architectures on well-known benchmarking datasets. Our code is available.

[Pre-print][icpr-pre-print] |
[Code](https://github.com/Boazrciasn/Quaternion-Capsule-Networks)
<!---[bibtex](_bibtex/quaternion-capsules.html)-->
<!---| [Poster][icpr-poster?oral]-->

```
@misc{zcan2020quaternion, 
      title={Quaternion Capsule Networks}, 
      author={Barış Özcan and Furkan Kınlı and Furkan Kıraç},
      year={2020},
      eprint={2007.04389},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
      }
```

[icpr-pre-print]: https://arxiv.org/pdf/2007.04389.pdf