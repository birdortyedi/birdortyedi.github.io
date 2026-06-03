---
title: "Re: Spatial-Adaptive Network for Single Image Denoising"
authors: "S. Menteş, F. Kınlı, B. Özcan, F. Kıraç"
collection: publications
permalink: /publication/2021-04-01-sadnet-img-denoising-number-7
excerpt: ''
header:
  teaser: publications/sadnet-thumb.jpg
date: 2021-04-01
venue: 'ML Reproducibility Challenge 2020, Accepted to ReScience Journal Publication'
paperurl: 'https://zenodo.org/record/4834672/files/article.pdf'
citation: 'Menteş, S., Kınlı, F., Özcan, B., & Kıraç, F. [Re] Spatial-Adaptive Network for Single Image Denoising. In ML Reproducibility Challenge 2020.'
---

![][image-ref]{: .img-rounded}

## Abstract
In this study, we present our results and experience during replicating the paper titled "Spatial-Adaptive Network for Single Image Denoising". This paper proposes novel spatial-adaptive denoising architecture for efficient noise removal by leveraging the deformable convolutions to adapt spatial information (i.e. edges and textures). We have implemented the model from scratch in PyTorch framework, and then have conducted real and synthetic noise experiments on the corresponding datasets. We have achieved to reproduce the results qualitatively and quantitatively.

[Re-Science][re-science-report]{: .btn .btn--info} [OpenReview][ml-reprod-report]{: .btn .btn--info} [Code][code-link]{: .btn .btn--info}

Bibtex:
{% raw %}
```
@article{Mentes:2021,
  author = {Menteş, Sami and Kınlı, Furkan and Özcan, Barış and Kıraç, Furkan},
  title = {{[Re] Spatial-Adaptive Network for Single Image Denoising}},
  journal = {ReScience C},
  year = {2021},
  month = may,
  volume = {7},
  number = {2},
  pages = {{#12}},
  doi = {10.5281/zenodo.4834672},
  url = {https://zenodo.org/record/4834672/files/article.pdf},
  code_url = {https://github.com/sami-automatic/SADNet_Replication},
  code_doi = {},
  code_swh = {swh:1:dir:1c60d43a0fe927c1f1287adefd252804c2f273b9},
  data_url = {},
  data_doi = {},
  review_url = {https://openreview.net/forum?id=yiAI9QN9nYt&noteId=SMFjCY6qG8},
  type = {Replication},
  language = {Python},
  domain = {ML Reproducibility Challenge 2020},
  keywords = {image denoising, image restoration, image processing}
}
```
{% endraw %}

[ml-reprod-report]: https://openreview.net/pdf?id=yiAI9QN9nYt
[re-science-report]: https://zenodo.org/record/4834672/files/article.pdf
[code-link]: https://github.com/sami-automatic/SADNet_Replication
[image-ref]: /images/publications/sadnet-results.jpg