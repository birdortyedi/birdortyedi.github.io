---
title: "Modeling the Lighting as Style Factor via Neural Networks for White Balance Correction"
authors: "Osman Furkan Kınlı"
collection: publications
permalink: /publications/phd-thesis/
excerpt: ''
date: 2025-05-12
venue: "Ph.D. Thesis, Özyeğin University"
paperurl: 'https://birdortyedi.github.io/files/phd-thesis.pdf'
header:
  teaser: publications/phd-thesis-thumb.png
type: thesis
short_venue: "PhD Thesis, Özyeğin University, 2025"
links:
  - label: "PDF"
    url: "/files/phd-thesis.pdf"
  - label: "Slides"
    url: "/files/phd-def-slides.pdf"
bibtex: |
  @phdthesis{kinli2025modeling,
    title={Modeling the Lighting as Style Factor via Neural Networks for White Balance Correction},
    author={K{\i}nl{\i}, Osman Furkan},
    year={2025},
    month={may},
    school={{\"O}zye{\u{g}}in University}
  }
---

Advised by [M. Furkan Kıraç](https://scholar.google.com/citations?user=kdJBxv8AAAAJ). Defended on May 12, 2025.

## Abstract
This thesis explores White Balance (WB) correction by modeling lighting as a style factor through distribution-based approaches in both architectural design and optimization frameworks. Three novel methods are proposed to address the challenges of complex illumination scenarios. The first approach, Style WB, employs a UNet-like architecture with style modulation to effectively remove illumination-related style information, which achieves robust correction with enhanced spatial consistency. The second approach, FDM WB, introduces feature distribution matching within the Uformer architecture, which enables precise alignment of global and local illumination features for WB correction. Both approaches are evaluated on the Cube+ dataset and a synthetic multi-illuminant benchmark, and they demonstrate substantial improvements in WB correction across diverse lighting conditions. The third approach, FDM Loss, defines an optimization framework leveraging the [CLS] token of Vision Transformers to achieve exact matching of all moments between the predicted and ground truth images, capturing higher-order statistics essential for managing intricate lighting variations. This approach delivers reduced Mean Angular Error (MAE) and consistent illumination correction on the LSMI dataset across three camera setups. While these methods advance WB correction, integrating deterministic mapping mechanisms, such as DeNIM, in resource-constrained environments or leveraging diffusion-based models and neural ODEs could further enhance performance, particularly in handling complex lighting scenarios. This work redefines the role of distribution-based modeling in addressing illumination challenges, setting a foundation for future innovations in image restoration.
