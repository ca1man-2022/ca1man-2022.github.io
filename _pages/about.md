---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
excerpt: "Tingyi Cai studies reliable graph and hypergraph learning, with a focus on out-of-distribution detection and generalization."
---

I am a Ph.D. student in Computer Science and Technology at [Zhejiang Normal University (ZJNU)](https://www.zjnu.edu.cn/main.htm), advised by Prof. Yunliang Jiang. I am also a visiting Ph.D. student at [Nanyang Technological University (NTU)](https://www.ntu.edu.sg/), Singapore, working with [Prof. Kelin Xia](https://personal.ntu.edu.sg/XIAKELIN/). I received my B.S. in Computer Science and Technology from ZJNU in 2023.

My research focuses on **reliable learning on graphs and hypergraphs**. I study how models detect out-of-distribution data, generalize under distribution shifts, and respond to adversarial changes in relational structure.

[Publications](/publications/) · [Google Scholar](https://scholar.google.cz/citations?user=taYw6VsAAAAJ&hl=zh-CN) · [GitHub](https://github.com/ca1man-2022) · [中文简介](/chinese/)

## Selected publications

{% assign selected_papers = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_papers %}
  {% include publication-card.html %}
{% endfor %}

[All publications and survey](/publications/)

## Recent news

- **Oct 2026** · Updated the [Graph OOD Detection Survey repository](https://github.com/ca1man-2022/Awesome-GOOD-Detection) with recent papers and a revised classification.
- **May 2026** · Received ZJNU’s Top Ten Outstanding Students Award and Li Xing · Endeavor Award.
- **May 2026** · Presented a poster at CGML 2026 in Changchun, Jilin.
- **Apr 2026** · CEGNN was accepted at FLINS-ISKE 2026 and received an Outstanding Student Paper Award.
- **Jan 2026** · Presented HyperGOOD at AAAI 2026 in Singapore.
- **Dec 2025** · Selected for the [CAST Doctoral Student Program](https://kecaihui-tm-zz.cast.org.cn/specialPage/web?type=qtgc).

[Earlier updates](/news/)

## Academic service

**Conference reviewer:** NeurIPS, AAAI.

**Journal reviewer:** IEEE Transactions on Systems, Man, and Cybernetics: Systems; Neural Networks; Applied Soft Computing; Frontiers in Artificial Intelligence; Frontiers in Robotics and AI (Robot Learning and Evolution).

## Elsewhere

I share reading notes on [CSDN](https://blog.csdn.net/bocaiaichila?type=blog).
