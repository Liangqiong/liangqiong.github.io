---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my full publication list on my [Google Scholar profile](https://scholar.google.com/citations?user=ruKpgzwAAAAJ&hl=zh-CN) or my [Researchgate profile](https://www.researchgate.net/profile/Liangqiong-Qu-2).

* [TMI 2023] Label-Efficient Self-Supervised Federated Learning for Tackling Data Heterogeneity in Medical Imaging. Rui Yan, ***Liangqiong Qu***, Qingyue Wei, Shih-Cheng Huang, Liyue Shen, Daniel Rubin, Lei Xing, Yuyin Zhou. ([Paper](https://ieeexplore-ieee-org.eproxy.lib.hku.hk/stamp/stamp.jsp?tp=&arnumber=10004993&tag=1), [Code](https://github.com/rui-yan/SSL-FL))
* [IEEE JBHI 2022] Splitavg: A heterogeneity-aware federated deep learning method for medical imaging. Miao Zhang, ***Liangqiong Qu***, Praveer Singh, Jayashree Kalpathy-Cramer, Daniel L. Rubin. (Co-corresponding authors) ([Paper](https://ieeexplore.ieee.org/abstract/document/9806163), [Code](https://github.com/zm17943/SplitAVG))


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
