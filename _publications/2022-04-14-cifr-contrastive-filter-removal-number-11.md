---
title: "Patch-wise Contrastive Style Learning for Instagram Filter Removal"
collection: publications
permalink: /publication/2022-04-14-cifr-contrastive-filter-removal-number-11
excerpt: ''
date: 2022-04-14
venue: 'NTIRE2022: New Trends in Image Restoration and Enhancement workshop
and challenges on image and video processing
in conjunction with CVPR 2022'
paperurl: ''
citation: 'Kınlı, F., Özcan, B., & Kıraç, F. (2022). Patch-wise Contrastive Style Learning for Instagram Filter Removal. arXiv preprint arXiv:2204.07486.'
---

## Abstract
Image-level corruptions and perturbations degrade the performance of CNNs on different downstream vision tasks. Social media filters are one of the most common resources of various corruptions and perturbations for real-world visual analysis applications. The negative effects of these distractive factors can be alleviated by recovering the original images with their pure style for the inference of the downstream vision tasks. Assuming these filters substantially inject a piece of additional style information to the social media images, we can formulate the problem of recovering the original versions as a reverse style transfer problem. We introduce Contrastive Instagram Filter Removal Network (CIFR), which enhances this idea for Instagram filter removal by employing a novel multi-layer patch-wise contrastive style learning mechanism. Experiments show our proposed strategy produces better qualitative and quantitative results than the previous studies. Moreover, we present the results of our additional experiments for proposed architecture within different settings. Finally, we present the inference outputs and quantitative comparison of filtered and recovered images on localization and segmentation tasks to encourage the main motivation for this problem.

<span style="color:red">Accepted as Oral Presentation.</span>

[Paper][ntire-paper] |
[arXiv][ntire-pre-print] |
[Code](https://github.com/birdortyedi/cifr-pytorch) |
[Demo](https://huggingface.co/spaces/birdortyedi/cifr-pytorch)


[ntire-pre-print]: https://arxiv.org/pdf/2204.07486.pdf
[ntire-paper]: https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Kinli_Patch-Wise_Contrastive_Style_Learning_for_Instagram_Filter_Removal_CVPRW_2022_paper.pdf
