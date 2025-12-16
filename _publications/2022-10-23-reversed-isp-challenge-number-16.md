---
title: "Reversed Image Signal Processing and RAW Reconstruction. AIM 2022 Challenge Report"
collection: publications
permalink: /publication/2022-10-23-reversed-isp-challenge-number-16
excerpt: ''
date: 2022-10-23
venue: 'AIM2022: Advances in Image Manipulation workshop in conjunction with ECCV 2022'
paperurl: ''
citation: 'Conde, M. V., Timofte, R., Huang, Y., Peng, J., Chen, C., Li, C., ... & Ju Jung, Y. (2022, October). Reversed image signal processing and RAW reconstruction. AIM 2022 challenge report. In European Conference on Computer Vision (pp. 3-26). Springer.'
header:
  teaser: 'publications/reversed-isp-chal-thumb.jpg'
---

![][arch]{: .img-rounded}

## Abstract
Cameras capture sensor RAW images and transform them into pleasant RGB images, suitable for the human eyes, using their integrated Image Signal Processor (ISP). Numerous low-level vision tasks operate in the RAW domain (e.g. image denoising, white balance) due to its linear relationship with the scene irradiance, wide-range of information at 12bits, and sensor designs. Despite this, RAW image datasets are scarce and more expensive to collect than the already large and public RGB datasets. This paper introduces the AIM 2022 Challenge on Reversed Image Signal Processing and RAW Reconstruction. We aim to recover raw sensor images from the corresponding RGBs without metadata and, by doing this, "reverse" the ISP transformation. The proposed methods and benchmark establish the state-of-the-art for this low-level vision inverse problem, and generating realistic raw sensor readings can potentially benefit other tasks such as denoising and super-resolution.

<span style="color:red">Accepted as Oral Presentation.</span>

<!-- [Paper][ntire-paper] | -->
[arXiv][aim-pre-print] | [Challenge][challenge]


[aim-pre-print]: https://arxiv.org/pdf/2210.11153.pdf
[challenge]: https://codalab.lisn.upsaclay.fr/competitions/5080
[arch]: /images/publications/reversed-isp-chal-arch.jpg

