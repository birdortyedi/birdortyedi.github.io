---
title: "Photography Retouching Transfer, NTIRE 2026 Challenge: Report"
authors: "O. Elezabi, M.V. Conde, Z. Wu, ..., F. Kınlı, ..., R. Timofte"
collection: publications
permalink: /publications/ntire-2026-retouching-transfer-challenge/
excerpt: ''
date: 2026-05-16
venue: 'NTIRE 2026: New Trends in Image Restoration and Enhancement workshop and challenges in conjunction with CVPR 2026'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2026W/NTIRE/papers/Elezabi_Photography_Retouching_Transfer_NTIRE_2026_Challenge_Report_CVPRW_2026_paper.pdf'
header:
  teaser: publications/ntire26-retouching-thumb.jpg
type: challenge
short_venue: "CVPRW 2026 · NTIRE"
awards: ["1st place"]
links:
  - label: "Paper"
    url: "https://openaccess.thecvf.com/content/CVPR2026W/NTIRE/papers/Elezabi_Photography_Retouching_Transfer_NTIRE_2026_Challenge_Report_CVPRW_2026_paper.pdf"
bibtex: |
  @inproceedings{elezabi2026photography,
    title={Photography Retouching Transfer, NTIRE 2026 Challenge: Report},
    author={Elezabi, Omar and Conde, Marcos V and Wu, Zongwei and Jin, Yeying and Timofte, Radu and K{\i}nl{\i}, Furkan and others},
    booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    pages={1796--1806},
    year={2026}
  }
---

## Abstract
This report is an overview of the NTIRE 2026 Photography Retouching Transfer Challenge. This competition is proposed to develop methods for transferring photography retouches applied to a reference image to advance reference-based image editing techniques. Participants are required to develop a method that learns and extracts the retouching applied to a reference, represented as an image before and after editing, and applies it to a new input while preserving image quality and fidelity. The challenge included a total of 76 participants with 7 submissions to the final test phase. Full-reference evaluation metrics were utilized as an initial ranking to identify the top methods, which are then included in a user study conducted by imaging experts to decide on the final ranking. This report describes the competition framework, the composition of the utilized datasets, the evaluation process, and the details of the top solutions. Top performing methods follow the same direction as the baseline by utilizing Implicit Neural Representation with test-time optimization, while adopting other techniques like meta-learning and iterative refinement for a more stable optimization and better generalizability. A comprehensive analysis of the challenge submissions is provided, highlighting the effectiveness and limitations of the proposed methods.
