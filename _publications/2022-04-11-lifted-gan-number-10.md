---
title: "[Re] Lifting 2D StyleGAN for 3D-Aware Face Generation"
collection: publications
permalink: /publication/2022-04-11-lifted-gan-number-10
excerpt: ''
date: 2022-04-11
venue: 'ML Reproducibility Challenge 2021 (Fall Edition), Accepted to ReScience Journal Publication'
paperurl: 'https://openreview.net/pdf?id=BcNonfQ3RY'
citation: 'Yılmaz, D., Kınlı, F., Özcan, B., & Kıraç, F. (2021). [Re] Lifting 2D StyleGAN for 3D-Aware Face Generation. In ML Reproducibility Challenge 2021 (Fall Edition).'
---

## Abstract
In this study, we present our results and experience during replicating the paper titled "Lifting 2D StyleGAN for 3D-Aware Face Generation". This work proposes a model, called LiftedGAN, that disentangles the latent space of StyleGAN2 into texture, shape, viewpoint, lighting components and utilizes those components to render novel synthetic images. This approach claims to enable the ability of manipulating viewpoint and lighting components separately without altering other features of the image. We have trained the proposed model in PyTorch, and have conducted all experiments presented in the original work. Thereafter, we have written the evaluation code from scratch. Our re-implementation enables us to better compare different models inferring on the same latent vector input. We were able to reproduce most of the results presented in the original paper both qualitatively and quantitatively.

[Report][paper-link] | [Code][code-link]

Bibtex:
```
@inproceedings{yilmaz2021re,
  title={[Re] Lifting 2D StyleGAN for 3D-Aware Face Generation},
  author={Y{\i}lmaz, Do{\u{g}}a and K{\i}nl{\i}, Furkan and {\"O}zcan, Bar{\i}{\c{s}} and K{\i}ra{\c{c}}, Furkan},
  booktitle={ML Reproducibility Challenge 2021 (Fall Edition)},
  year={2021}
}
```

[paper-link]: https://openreview.net/pdf?id=BcNonfQ3RY
[code-link]: https://github.com/yilmazdoga/lifting-2d-stylegan-for-3d-aware-face-generation