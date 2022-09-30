---
layout: archive
title: "Journal Papers"
permalink: /publications/
author_profile: true
---
Zijie Jin, *Wenjian Huang*, Ning Shen, Juan Li, Xiaochen Wang, Jiqiao Dong, Peter J Park, Ruibin Xi. Single-cell gene fusion detection by scFusion[J]. Nature communications, 2022, 13(1): 1-12.

*Wenjian Huang*, Weizheng Gao, Chao Hou, Dongxiao Zhang, Xiaoying Wang, Jue Zhang. Simultaneous vessel segmentation and unenhanced prediction using self-supervised dual-task learning in 3D CTA (SVSUP). Computer Methods and Programs in Biomedicine, 2022, 224: 107001.

Jiahao Xia, Weiwei Qu, *Wenjian Huang*, Jianguo Zhang, Xi Wang, Min Xu. Sparse Local Patch Transformer for Robust Face Alignment and Landmarks Inherent Relation Learning. CVPR 2022. [[PDF]](http://academicpages.github.io/files/paper3.pdf)

---
layout: archive
title: "Conference Papers"
permalink:
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
