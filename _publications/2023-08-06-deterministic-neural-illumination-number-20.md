---
title: "Deterministic Neural Illumination Mapping for Efficient Auto-White Balance Correction"
collection: publications
permalink: /publication/2023-08-06-deterministic-neural-illumination-number-20
excerpt: ''
date: 2023-08-06
venue: 'RCV 2023: The 1st ICCV 2023 Workshop on Resource Efficient Deep Learning for Computer Vision'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2023W/RCV/papers/Kinli_Deterministic_Neural_Illumination_Mapping_for_Efficient_Auto-White_Balance_Correction_ICCVW_2023_paper.pdf'
citation: 'Kınlı, F., Yılmaz, D., Özcan, B., & Kıraç, F. (2023). Deterministic neural illumination mapping for efficient auto-white balance correction. In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 1139-1147).'
---

## Abstract

Auto-white balance (AWB) correction is a critical operation in image signal processors for accurate and consistent color correction across various illumination scenarios. This paper presents a novel and efficient AWB correction method that achieves at least 35 times faster processing with equivalent or superior performance on high-resolution images for the current state-of-the-art methods. Inspired by deterministic color style transfer, our approach introduces deterministic illumination color mapping, leveraging learnable projection matrices for both canonical illumination form and AWB-corrected output. It involves feeding highresolution images and corresponding latent representations into a mapping module to derive a canonical form, followed by another mapping module that maps the pixel values to those for the corrected version. This strategy is designed as resolution-agnostic and also enables seamless integration of any pre-trained AWB network as the backbone. Experimental results confirm the effectiveness of our approach, revealing significant performance improvements and reduced
time complexity compared to state-of-the-art methods. Our method provides an efficient deep learning-based AWB correction solution, promising real-time, high-quality color correction for digital imaging applications. Source code is available at https://github.com/birdortyedi/DeNIM/

[Paper][paper-link]

Bibtex:
```
@inproceedings{kinli2023deterministic,
  title={Deterministic neural illumination mapping for efficient auto-white balance correction},
  author={K{\i}nl{\i}, Furkan and Y{\i}lmaz, Do{\u{g}}a and {\"O}zcan, Bar{\i}{\c{s}} and K{\i}ra{\c{c}}, Furkan},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={1139--1147},
  year={2023}
}
```

[paper-link]: https://openaccess.thecvf.com/content/ICCV2023W/RCV/papers/Kinli_Deterministic_Neural_Illumination_Mapping_for_Efficient_Auto-White_Balance_Correction_ICCVW_2023_paper.pdf
