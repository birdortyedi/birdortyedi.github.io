---
title: "[Re] Lifting 2D StyleGAN for 3D-Aware Face Generation"
collection: publications
permalink: /publication/2022-04-11-lifted-gan-number-10
excerpt: ''
date: 2022-04-11
venue: 'ML Reproducibility Challenge 2021 (Fall Edition), Accepted to ReScience Journal Publication'
paperurl: ''
citation: 'Doğa Yılmaz, Furkan Kınlı, Barış Özcan and Furkan Kıraç. (2022). [Re] Lifting 2D StyleGAN for 3D-Aware Face Generation. ML Reproducibility Challenge 2021 (Fall Edition). https://openreview.net/forum?id=BcNonfQ3RY'
---

## Abstract
In this study, we present our results and experience during replicating the paper titled "Lifting 2D StyleGAN for 3D-Aware Face Generation". This work proposes a model, called LiftedGAN, that disentangles the latent space of StyleGAN2 into texture, shape, viewpoint, lighting components and utilizes those components to render novel synthetic images. This approach claims to enable the ability of manipulating viewpoint and lighting components separately without altering other features of the image. We have trained the proposed model in PyTorch, and have conducted all experiments presented in the original work. Thereafter, we have written the evaluation code from scratch. Our re-implementation enables us to better compare different models inferring on the same latent vector input. We were able to reproduce most of the results presented in the original paper both qualitatively and quantitatively.

[Report][ml-reprod-report] |
[Code](https://github.com/yilmazdoga/lifting-2d-stylegan-for-3d-aware-face-generation)


Bibtex:
```
@inproceedings{
    yilmaz2022re,
    title={[Re] Lifting 2D Style{GAN} for 3D-Aware Face Generation},
    author={Do{\u{g}}a Y{\i}lmaz and Furkan K{\i}nl{\i} and Bar{\i}{\c{s}} {\"O}zcan and Furkan K{\i}ra{\c{c}}},
    booktitle={ML Reproducibility Challenge 2021 (Fall Edition)},
    year={2022},
    url={https://openreview.net/forum?id=BcNonfQ3RY}
}
```

[ml-reprod-report]: https://openreview.net/pdf?id=BcNonfQ3RY