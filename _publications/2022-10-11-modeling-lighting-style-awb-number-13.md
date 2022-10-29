---
title: "Modeling the Lighting in Scenes as Style for Auto White-Balance Correction"
collection: publications
permalink: /publication/2022-10-11-modeling-lighting-style-awb-number-13
excerpt: ''
date: 2022-10-11
venue: 'IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2023'
paperurl: ''
citation: 'Kınlı, F., Yılmaz, D., Özcan, B., and Kıraç, F. (2022). Modeling the Lighting in Scenes as Style for Auto White-Balance Correction. arXiv preprint arXiv:22210.09090.'
---

## Abstract
Style may refer to different concepts (e.g. painting style, hairstyle, texture, color, filter, etc.) depending on how the feature space is formed. In this work, we propose a novel idea of interpreting the lighting in the single- and multi-illuminant scenes as the concept of style. To verify this idea, we introduce an enhanced auto white-balance (AWB) method that models the lighting in single- and mixed-illuminant scenes as the style factor. Our AWB method does not require any illumination estimation step, yet contains a network learning to generate the weighting maps of the images with different WB settings. Proposed network utilizes the style information, extracted from the scene by a multi-head style extraction module. AWB correction is completed after blending these weighting maps and the scene. Experiments on single- and mixedilluminant datasets demonstrate that our proposed method achieves promising correction results when compared to the recent works. This shows that the lighting in the scenes with multiple illuminations can be modeled by the concept of style. Source code and trained models are available on https://github.com/birdortyedi/lighting-as-style-awb-correction.

<!-- [Paper][style-awb-paper] | -->
[arXiv][style-awb-pre-print] |
[Code](https://github.com/birdortyedi/lighting-as-style-awb-correction) 


[style-awb-pre-print]: https://arxiv.org/pdf/2210.09090.pdf
