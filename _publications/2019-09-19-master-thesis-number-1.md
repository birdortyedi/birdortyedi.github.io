---
title: "Clothing Image Retrieval with Triplet Capsule Networks"
collection: publications
permalink: /publication/2019-09-19-master-thesis-number-1
excerpt: 'Master's Thesis'
date: 2019-09-19
venue: 'Özyeğin University'
paperurl: 'files/msc-thesis.pdf'
citation: 'F. Kinli. Clothing Image Retrieval with Triplet Capsule Networks. (Master’s thesis, Özyeğin University, Istanbul, Turkey), 2019.'
---

## Abstract

Clothing image retrieval has become more important after some major developments in Computer Science and the emergence of e-commerce. Recent studies generally attack to this problem by using Convolutional Neural Networks (CNNs). Despite its popularity, CNNs, by their nature, have some intrinsic limitations such as losing hi- erarchical spatial relationship between the parts of an image, and being not robust to affine transformations. Most recently proposed network architecture, namely Capsule Networks, has the ability to overcome these limitations by preserving the part-whole relationship and pose information in the images. In this thesis, we investigate in-shop clothing retrieval performance of densely-connected Capsule Networks with dynamic routing. To achieve this, we propose Triplet-based designs of Capsule Network ar- chitecture with two different feature extraction methods: Stacked-convolutional (SC- CapsNet) and Residual-connected (RCCapsNet) Capsule Networks. Experimental results of our proposed designs on in-shop clothing retrieval show that SCCapsNet achieves 32.1% Top-1, 81.8% Top-20, and 90.0% Top-50 recall-at-K scores; whereas RCCapsNet has even better performance with 33.9% Top-1, 84.6% Top-20, and 92.6% Top-50 recall-at-K scores. These figures demonstrate that both of our designs outper- form the baseline study and the earlier approaches by a wide margin without using any extra supportive information besides to the images. Moreover, when compared to the SOTA architectures on clothing retrieval, our proposed Triplet Capsule Networks achieve comparable recall rates with only half of the parameters used in the SOTA architectures. In the future, our designs may inherit extra performance boost due to advances in the relatively new Capsule Network research.


[PDF](files/msc-thesis.pdf) |
[Code](https://github.com/birdortyedi/image-retrieval-with-capsules) |
[Slides](files/msc-def-slides.pdf)
