---
title: "Reversing Image Signal Processors by Reverse Style Transferring"
authors: "F. Kınlı, B. Özcan, F. Kıraç"
collection: publications
permalink: /publication/2022-10-23-reverse-style-transfer-reversed-isp-number-14
excerpt: ''
date: 2022-10-23
venue: 'AIM2022: Advances in Image Manipulation workshop
in conjunction with ECCV 2022'
paperurl: 'https://arxiv.org/pdf/2210.09074'
citation: 'Kınlı, F., Özcan, B., & Kıraç, F. (2022, October). Reversing image signal processors by reverse style transferring. In European Conference on Computer Vision (pp. 688-698). Springer.'
header:
  teaser: 'publications/reversed-isp-chal-arch.jpg'
---

![][results]{: .img-rounded}

## Abstract
RAW image datasets are more suitable than the standard RGB image datasets for the ill-posed inverse problems in low-level vision, but not common in the literature. There are also a few studies to focus on mapping sRGB images to RAW format. Mapping from sRGB to RAW format could be a relevant domain for reverse style transferring since the task is an ill-posed reversing problem. In this study, we seek an answer to the question: Can the ISP operations be modeled as the style factor in an end-to-end learning pipeline? To investigate this idea, we propose a novel architecture, namely RST-ISP-Net, for learning to reverse the ISP operations with the help of adaptive feature normalization. We formulate this problem as a reverse style transferring and mostly follow the practice used in the prior work. We have participated in the AIM Reversed ISP challenge with our proposed architecture. Results indicate that the idea of modeling disruptive or modifying factors as style is still valid, but further improvements are required to be competitive in such a challenge.

<span style="color:red">Accepted as Oral Presentation.</span>

<!-- [Paper][ntire-paper] | -->
[Paper][aim-pre-print]{: .btn .btn--info} [Code][code-link]{: .btn .btn--info}

Bibtex:
```
@inproceedings{kinli2022reversing,
  title={Reversing image signal processors by reverse style transferring},
  author={K{\i}nl{\i}, Furkan and {\"O}zcan, Bar{\i}{\c{s}} and K{\i}ra{\c{c}}, Furkan},
  booktitle={European Conference on Computer Vision},
  pages={688--698},
  year={2022},
  organization={Springer}
}
```

[paper-link]: https://arxiv.org/pdf/2210.09074
[code-link]: https://github.com/birdortyedi/reversed-isp-pytorch
[results]: /images/publications/reversed-style-isp-results.jpg

