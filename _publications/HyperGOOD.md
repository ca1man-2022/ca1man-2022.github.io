---
title: 'HyperGOOD: Towards Out-of-Distribution Detection in Hypergraphs'
collection: publications
category: conferences
venue: AAAI
date: 2026-03-14
permalink: /publication/HyperGOOD
excerpt: Energy-based hypergraph out-of-distribution detection using multi-scale spectral information and structure-aware uncertainty propagation.
paperurl: https://ojs.aaai.org/index.php/AAAI/article/view/39064
citation: 'Cai, T., Jiang, Y., Li, M., Huang, C., Fang, Y., Gao, C., & Zheng, Z. (2026). HyperGOOD: Towards Out-of-Distribution Detection in Hypergraphs. Proceedings of the AAAI Conference on Artificial Intelligence, 40(24), 19817–19825.'
authors: T. Cai, Y. Jiang, M. Li, C. Huang, Y. Fang, C. Gao, and Z. Zheng
selected: true
codeurl: https://github.com/ca1man-2022/HyperGOOD
---

Out-of-distribution (OOD) detection plays a critical role in ensuring the robustness of machine learning models in open-world settings. While extensive efforts have been made in vision, language, and graph domains, the challenge of OOD detection in hypergraph-structured data remains unexplored. In this work, we formalize the problem of hypergraph out-of-distribution (HOOD) detection, which aims to identify nodes or hyperedges whose high-order relational contexts differ significantly from those seen during training. We propose HyperGOOD, a unified energy-based detection framework that integrates multi-scale spectral decomposition with structure-aware uncertainty propagation. By preserving both low- and high-frequency signals and diffusing uncertainty across the hypergraph, HyperGOOD effectively captures subtle and relationally entangled anomalies. Experimental results on nine hypergraph datasets demonstrate the effectiveness of our approach, establishing a new foundation for robust hypergraph learning under distributional shifts.
