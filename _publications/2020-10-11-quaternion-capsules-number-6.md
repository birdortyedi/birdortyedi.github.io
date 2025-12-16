---
title: "Quaternion Capsule Networks"
collection: publications
permalink: /publication/2020-10-11-quaternion-capsules-number-6
excerpt: ''
header:
  teaser: publications/quat-caps-net-thumb.jpg
date: 2020-10-11
venue: '25th International Conference on Pattern Recognition, ICPR2020'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9412006'
citation: 'Özcan, B., Kinli, F., & Kiraç, F. (2021, January). Quaternion capsule networks. In 2020 25th International Conference on Pattern Recognition (ICPR) (pp. 6858-6865). IEEE.'
---

![][image-ref]{: .img-rounded}

## Abstract
Capsules are grouping of neurons that allow to represent sophisticated information of a visual entity such as pose and features. In the view of this property, Capsule Networks outperform CNNs in challenging tasks like object recognition in unseen viewpoints, and this is achieved by learning the transformations between the object and its parts with the help of high dimensional representation of pose information. In this paper, we present Quaternion Capsules (QCN) where pose information of capsules and their transformations are represented by quaternions. Quaternions are immune to the gimbal lock, have straightforward regularization of the rotation representation for capsules, and require less number of parameters than matrices. The experimental results show that QCNs generalize better to novel viewpoints with fewer parameters, and also achieve on-par or better performances with the state-of-the-art Capsule architectures on well-known benchmarking datasets. Our code is available.

[Paper][paper-link] | [Code][code-link]


Bibtex:
```
@inproceedings{ozcan2021quaternion,
  title={Quaternion capsule networks},
  author={Ozcan, Baris and K{\i}nl{\i}, Furkan and K{\i}ra{\c{c}}, Furkan},
  booktitle={2020 25th International Conference on Pattern Recognition (ICPR)},
  pages={6858--6865},
  year={2021},
  organization={IEEE}
}
```

[paper-link]: https://ieeexplore.ieee.org/abstract/document/9412006
[code-link]: https://github.com/Boazrciasn/Quaternion-Capsule-Networks
[image-ref]: /images/publications/quat-caps-net-arch.jpg