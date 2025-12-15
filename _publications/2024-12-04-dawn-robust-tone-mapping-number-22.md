---
title: "Dawn: A Robust Tone Mapping Operator for Multi-Illuminant and Low-Light Scenarios"
collection: publications
permalink: /publication/2024-12-04-dawn-robust-tone-mapping-number-22
excerpt: ''
date: 2024-12-04
venue: 'VISIGRAPP 2025: 20th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications'
paperurl: 'https://www.scitepress.org/Link.aspx?doi=10.5220/0013134600003912'
citation: 'Kınlı, F., Özcan, B. and Kıraç, F. (2025). Dawn: A Robust Tone Mapping Operator for Multi-Illuminant and Low-Light Scenarios. In Proceedings of the 20th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications - Volume 3: VISAPP'
header:
  teaser: 'dawn-tmo-thumb.jpg'
---

![][results]{: .img-rounded}

## Abstract

We introduce Dawn, a novel Tone Mapping Operator (TMO) designed to address the limitations of state-of-the-art TMOs such as Flash and Storm, particularly in challenging lighting conditions. While existing methods perform well in stable, well-lit, single-illuminant environments, they struggle with multi-illuminant and low-light scenarios, often leading to artifacts, amplified noise, and color shifts due to the additional step to adjust overall scene brightness. Dawn solves these issues by adaptively inferring the scaling parameter for the Naka-Rushton Equation through a weighted combination of luminance mean and variance. This dynamic approach allows Dawn to handle varying illuminant conditions, reducing artifacts and improving image quality without requiring additional adjustments to scene brightness. Our experiments show that Dawn matches the performance of current state-of-the-art TMOs on HDR datasets and outperforms them in low-light conditions, providing superior visual results. The source code for Dawn will be available at https://github.com/birdortyedi/ dawn-tmo/.

<span style="color:red">Accepted as Oral Presentation.</span>

[Paper][paper-link]

Bibtex:
```
@conference{visapp25,
    author={Furkan Kınlı and Barış Özcan and Furkan Kıra\c{c}},
    title={Dawn: A Robust Tone Mapping Operator for Multi-Illuminant and Low-Light Scenarios},
    booktitle={Proceedings of the 20th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications - Volume 3: VISAPP},
    year={2025},
    pages={62-68},
    publisher={SciTePress},
    organization={INSTICC},
    doi={10.5220/0013134600003912},
    isbn={978-989-758-728-3},
    issn={2184-4321},
}
```


[paper-link]: https://www.scitepress.org/Link.aspx?doi=10.5220/0013134600003912
[results]: /images/dawn-tmo-results.jpg
