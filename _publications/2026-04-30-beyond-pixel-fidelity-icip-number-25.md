---
title: "Beyond Pixel Fidelity: Minimizing Perceptual Distortion and Color Bias in Night Photography Rendering"
collection: publications
permalink: /publication/2026-04-30-beyond-pixel-fidelity-icip-number-25
excerpt: ''
date: 2026-04-30
venue: 'IEEE International Conference on Image Processing (ICIP)'
paperurl: 'https://arxiv.org/pdf/2604.28136'
citation: 'Kınlı, F. Beyond Pixel Fidelity: Minimizing Perceptual Distortion and Color Bias in Night Photography Rendering. In Proceedings of the IEEE International Conference on Image Processing (ICIP), 2026.'
header:
  teaser: 'publications/beyond-pixel-fidelity-thumb.jpg'
---

![][arch]{: .img-rounded}

## Abstract
Night Photography Rendering (NPR) poses a significant challenge due to the extreme contrast between dark and illuminated areas in scenes, stemming from concurrent capture of severely dark regions alongside intense point light sources. Existing methods, which are mainly tailored for fidelity metrics, reveal considerable perceptual gaps and often detract from visual quality. We introduce pHVI-ISPNet, a novel RAW-to-RGB framework built on the robust HVI color space. Our network integrates four distinct key refinements: RAW-domain feature processing and Wavelet-based feature propagation to mitigate high-frequency detail loss; sample-based dynamic loss coefficients to ensure stable learning across varying exposure levels; and loss term based on feature distributions to maintain rigorous color constancy. Evaluations on the dataset introduced in the NTIRE 2025 challenge on NPR confirm our approach achieves competitive fidelity while establishing new state-of-the-art results in both CIE2000 color difference and LPIPS. This validates our perceptually-driven design for high-quality nighttime imaging.

[Paper][paper-link]

Bibtex:
```
@inproceedings{kinli2026beyond,
  title={Beyond Pixel Fidelity: Minimizing Perceptual Distortion and Color Bias in Night Photography Rendering},
  author={K{\i}nl{\i}, Furkan},
  booktitle={IEEE International Conference on Image Processing (ICIP)},
  year={2026}
}
```

[paper-link]: https://arxiv.org/pdf/2604.28136
[arch]: /images/publications/beyond-pixel-fidelity-arch.svg
