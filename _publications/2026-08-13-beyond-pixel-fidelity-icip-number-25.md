---
title: "Beyond Pixel Fidelity: Minimizing Perceptual Distortion and Color Bias in Night Photography Rendering"
authors: "F. Kınlı"
collection: publications
permalink: /publications/beyond-pixel-fidelity/
excerpt: ''
date: 2026-08-13  # online in IEEE Xplore (ICIP 2026 proceedings); accepted 2026-04-30
venue: '2026 IEEE International Conference on Image Processing (ICIP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11630277'
citation: 'Kınlı, F. Beyond Pixel Fidelity: Minimizing Perceptual Distortion and Color Bias in Night Photography Rendering. In Proceedings of the 2026 IEEE International Conference on Image Processing (ICIP), pp. 1-6, 2026.'
header:
  teaser: 'publications/beyond-pixel-fidelity-thumb.jpg'
selected: true
type: conference
short_venue: "ICIP 2026"
links:
  - label: "Paper"
    url: "https://ieeexplore.ieee.org/abstract/document/11630277"
  - label: "arXiv"
    url: "https://arxiv.org/pdf/2604.28136"
bibtex: |
  @inproceedings{kinli2026beyond,
    title={Beyond Pixel Fidelity: Minimizing Perceptual Distortion and Color Bias in Night Photography Rendering},
    author={K{\i}nl{\i}, Furkan},
    booktitle={2026 IEEE International Conference on Image Processing (ICIP)},
    pages={1--6},
    year={2026},
    doi={10.1109/ICIP61757.2026.11630277}
  }
---

![][arch]{: .img-rounded}

## Abstract
Night Photography Rendering (NPR) poses a significant challenge due to the extreme contrast between dark and illuminated areas in scenes, stemming from concurrent capture of severely dark regions alongside intense point light sources. Existing methods, which are mainly tailored for fidelity metrics, reveal considerable perceptual gaps and often detract from visual quality. We introduce pHVI-ISPNet, a novel RAW-to-RGB framework built on the robust HVI color space. Our network integrates four distinct key refinements: RAW-domain feature processing and Wavelet-based feature propagation to mitigate high-frequency detail loss; sample-based dynamic loss coefficients to ensure stable learning across varying exposure levels; and loss term based on feature distributions to maintain rigorous color constancy. Evaluations on the dataset introduced in the NTIRE 2025 challenge on NPR confirm our approach achieves competitive fidelity while establishing new state-of-the-art results in both CIE2000 color difference and LPIPS. This validates our perceptually-driven design for high-quality nighttime imaging.

[arch]: /images/publications/beyond-pixel-fidelity-arch.svg
