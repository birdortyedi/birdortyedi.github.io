---
title: "Modeling the Lighting in Scenes as Style for Auto White-Balance Correction"
collection: publications
permalink: /publication/2022-10-11-modeling-lighting-style-awb-number-13
excerpt: ''
date: 2022-10-11
venue: 'IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2023'
paperurl: 'https://openaccess.thecvf.com/content/WACV2023/papers/Kinli_Modeling_the_Lighting_in_Scenes_As_Style_for_Auto_White-Balance_WACV_2023_paper.pdf'
citation: 'Kınlı, F., Yılmaz, D., Özcan, B., & Kıraç, F. (2023). Modeling the lighting in scenes as style for auto white-balance correction. In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (pp. 4903-4913).'
header:
  teaser: 'style-awb-arch.jpg'
---

![][image-ref]{: .img-rounded}

## Abstract
Style may refer to different concepts (e.g. painting style, hairstyle, texture, color, filter, etc.) depending on how the feature space is formed. In this work, we propose a novel idea of interpreting the lighting in the single- and multi-illuminant scenes as the concept of style. To verify this idea, we introduce an enhanced auto white-balance (AWB) method that models the lighting in single- and mixed-illuminant scenes as the style factor. Our AWB method does not require any illumination estimation step, yet contains a network learning to generate the weighting maps of the images with different WB settings. Proposed network utilizes the style information, extracted from the scene by a multi-head style extraction module. AWB correction is completed after blending these weighting maps and the scene. Experiments on single- and mixedilluminant datasets demonstrate that our proposed method achieves promising correction results when compared to the recent works. This shows that the lighting in the scenes with multiple illuminations can be modeled by the concept of style. Source code and trained models are available on https://github.com/birdortyedi/lighting-as-style-awb-correction.

[Paper][paper-link] | [Code][code-link]

Bibtex:
```
@inproceedings{kinli2023modeling,
  title={Modeling the lighting in scenes as style for auto white-balance correction},
  author={K{\i}nl{\i}, Furkan and Y{\i}lmaz, Do{\u{g}}a and {\"O}zcan, Bar{\i}{\c{s}} and K{\i}ra{\c{c}}, Furkan},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={4903--4913},
  year={2023}
}
```

[paper-link]: https://openaccess.thecvf.com/content/WACV2023/papers/Kinli_Modeling_the_Lighting_in_Scenes_As_Style_for_Auto_White-Balance_WACV_2023_paper.pdf
[code-link]: https://github.com/birdortyedi/lighting-as-style-awb-correction
[image-ref]: /images/style-awb-arch.jpg