---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
excerpt: "Tingyi Cai studies reliable graph and hypergraph learning, with a focus on out-of-distribution detection and generalization."
---

<p class="research-label">GRAPH & HYPERGRAPH LEARNING</p>

I am a Ph.D. student in Computer Science and Technology at [Zhejiang Normal University (ZJNU)](https://www.zjnu.edu.cn/main.htm), advised by Prof. Yunliang Jiang. I am also a visiting Ph.D. student at [Nanyang Technological University (NTU)](https://www.ntu.edu.sg/), Singapore, working with [Assoc. Prof. Kelin Xia](https://personal.ntu.edu.sg/XIAKELIN/). I received my B.S. in Computer Science and Technology from ZJNU in 2023.

My research focuses on **reliable learning on graphs and hypergraphs**. I study how models detect out-of-distribution data, generalize under distribution shifts, and respond to adversarial changes in relational structure.

[Publications](/publications/) · [Google Scholar](https://scholar.google.cz/citations?user=taYw6VsAAAAJ&hl=zh-CN) · [GitHub](https://github.com/ca1man-2022) · [中文简介](/chinese/)

<nav class="section-nav" aria-label="On this page"><a href="#selected-publications">Selected research</a><a href="#news--milestones">News & milestones</a><a href="#academic-service">Academic service</a></nav>

## Selected publications

{% assign selected_papers = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_papers %}
  {% include publication-card.html %}
{% endfor %}

[All publications and survey](/publications/)

## News & milestones

<div class="news-timeline" markdown="1">
{% include homepage-news.md %}
</div>

## Academic service

**Conference reviewer:** NeurIPS, AAAI.

**Journal reviewer:** IEEE Transactions on Systems, Man, and Cybernetics: Systems; Neural Networks; Applied Soft Computing; Frontiers in Artificial Intelligence; Frontiers in Robotics and AI (Robot Learning and Evolution).

## Elsewhere

I share reading notes on [CSDN](https://blog.csdn.net/bocaiaichila?type=blog).

[CCF conference deadlines](https://ccfddl.com/)
