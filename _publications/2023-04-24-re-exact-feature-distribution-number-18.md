---
title: "[Re] Exact Feature Distribution Matching for Arbitrary Style Transfer and Domain Generalization"
authors: "M. Erkol, F. Kınlı, B. Özcan, F. Kıraç"
collection: publications
permalink: /publication/2023-04-24-re-exact-feature-distribution-number-18
excerpt: ''
date: 2023-04-24
venue: 'ML Reproducibility Challenge 2022 (ReScience Journal)'
paperurl: 'https://openreview.net/pdf?id=a5_hbZf0NB'
citation: 'Erkol, M., Kınlı, F., Özcan, B., & Kıraç, F. (2023). [Re] exact feature distribution matching for arbitrary style transfer and domain generalization. In ML Reproducibility Challenge 2022.'
header:
  teaser: 'publications/re_efdm-thumb.jpg'
---

![][arch]{: .img-rounded}

## Reproducibility Study
In this reproducibility study, we present our results and experience during replicating the paper, titled Exact Feature Distribution Matching for Arbitrary Style Transfer and
Domain Generalization [1]. In real‐world scenarios, the feature distributions are mostly much more complicated than Gaussian, so only mean and standard deviation may not
be fully representative to match them. This paper introduces a novel strategy to exactly match the histograms of image features via the Sort‐Matching algorithm in a computa‐
tionally feasible way. We were able to reproduce most of the results presented in the original paper both qualitatively and quantitatively.

[Paper][paper-link]{: .btn .btn--info} [Code][code-link]{: .btn .btn--info}

Bibtex:
```
@inproceedings{erkol2023re,
  title={[Re] exact feature distribution matching for arbitrary style transfer and domain generalization},
  author={Erkol, Mert and K{\i}nl{\i}, Furkan and {\"O}zcan, Bar{\i}{\c{s}} and K{\i}ra{\c{c}}, Furkan},
  booktitle={ML Reproducibility Challenge 2022},
  year={2023}
}
```

Original Paper:
```
@inproceedings{zhang2021exact,
  title={Exact Feature Distribution Matching for Arbitrary Style Transfer and Domain Generalization},
  author={Zhang, Yabin and Li, Minghan and Li, Ruihuang and Jia, Kui and Zhang, Lei},
  booktitle={CVPR},
  year={2022}
}
```

[paper-link]: https://openreview.net/pdf?id=a5_hbZf0NB
[code-link]: https://github.com/birdortyedi/efdm-pytorch
[arch]: /images/publications/re_efdm-arch.jpg