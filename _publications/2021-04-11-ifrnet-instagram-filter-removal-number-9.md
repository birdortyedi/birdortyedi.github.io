---
title: "Instagram Filter Removal on Fashionable Images"
collection: publications
permalink: /publication/2021-04-11-instagram-filter-removal-number-9
excerpt: ''
header:
  teaser: publications/ifrnet-thumb.jpg
date: 2021-04-11
venue: 'NTIRE2021: New Trends in Image Restoration and Enhancement workshop and challenges on image and video processing in conjunction with CVPR 2021'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Kinli_Instagram_Filter_Removal_on_Fashionable_Images_CVPRW_2021_paper.pdf'
citation: 'Kinli, F., Ozcan, B., & Kirac, F. (2021). Instagram filter removal on fashionable images. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 736-745).'
---

![][image-ref]{: .img-rounded}

## Abstract
Social media images are generally transformed by filtering to obtain aesthetically more pleasing appearances. However, CNNs generally fail to interpret both the image and its filtered version as the same in the visual analysis of social media images. We introduce Instagram Filter Removal Network (IFRNet) to mitigate the effects of image filters for social media analysis applications. To achieve this, we assume any filter applied to an image substantially injects a piece of additional style information to it, and we consider this problem as a reverse style transfer problem. The visual effects of filtering can be directly removed by adaptively normalizing external style information in each level of the encoder. Experiments demonstrate that IFRNet outperforms all compared methods in quantitative and qualitative comparisons, and has the ability to remove the visual effects to a great extent. Additionally, we present the filter classification performance of our proposed model, and analyze the dominant color estimation on the images unfiltered by all compared methods.

[Paper][paper-link] | [Code][code-link] | [Demo][demo-link]

Bibtex:
```
@inproceedings{kinli2021instagram,
  title={Instagram filter removal on fashionable images},
  author={Kinli, Furkan and Ozcan, Baris and Kirac, Furkan},
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},
  pages={736--745},
  year={2021}
}
```

[paper-link]: https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Kinli_Instagram_Filter_Removal_on_Fashionable_Images_CVPRW_2021_paper.pdf
[code-link]: https://github.com/birdortyedi/instagram-filter-removal-pytorch
[demo-link]: https://huggingface.co/spaces/birdortyedi/instagram-filter-removal
[image-ref]: /images/publications/ifrnet-arch.jpg