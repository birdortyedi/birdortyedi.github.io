---
permalink: /
title: "He lå e loi la"
seo_title: "Furkan Kınlı"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
![][me]

**Looking for the opportunities for highly competitive research fellowship or visiting scholar position.**

### About Me

*   I am currently working as a faculty member in the [Department of Artificial Intelligence][bau-ai] at [Bahçeşehir University][bau].

*   I received my Ph.D. (advised by [Assoc. Prof. Furkan Kıraç][fkirac]), M.Sc., and B.Sc. degrees in [Department of Computer Science][ozu-cs] at [Özyeğin University][ozu] (YES, Triple crown!).

*   My research interests focus on computational photography, image signal processors (ISP), night photography rendering, color science, and image restoration & enhancement.

*   Previously, I have worked on the downstream applications of computer vision, particularly using deep learning approaches, as well as the applications of generative modeling, image-to-image translation, fashion image understanding and capsule networks.


<p class="tags">{% for t in site.data.cv.interests %}<span class="badge">{{ t }}</span>{% endfor %}</p>

### Recently

{% include recently.html %}

### Recent News

{% include news.html limit=6 %}

[All news →](/news/)

[me]: /images/doomsdayblue.jpeg
[ozu-cs]: https://www.ozyegin.edu.tr/en/computer-science-department
[ozu]: https://www.ozyegin.edu.tr/en/
[fkirac]: https://scholar.google.com/citations?user=kdJBxv8AAAAJ
[bau]: https://bau.edu.tr/
[bau-ai]: https://bau.edu.tr/content/16491-about-artificial-intelligence-engineering-department
