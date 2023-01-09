---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find my full publication list on my [Google Scholar profile](https://scholar.google.com/citations?user=ruKpgzwAAAAJ&hl=zh-CN) or my [Researchgate profile](https://www.researchgate.net/profile/Liangqiong-Qu-2).

- [TMI 2023] Label-Efficient Self-Supervised Federated Learning for Tackling Data Heterogeneity in Medical Imaging. Rui Yan, ***Liangqiong Qu***, Qingyue Wei, Shih-Cheng Huang, Liyue Shen, Daniel Rubin, Lei Xing, Yuyin Zhou. ([Paper](https://ieeexplore-ieee-org.eproxy.lib.hku.hk/stamp/stamp.jsp?tp=&arnumber=10004993&tag=1), [Code](https://github.com/rui-yan/SSL-FL))
- [IEEE JBHI 2022] Splitavg: A heterogeneity-aware federated deep learning method for medical imaging. Miao Zhang, ***Liangqiong Qu***, Praveer Singh, Jayashree Kalpathy-Cramer, Daniel L. Rubin. (Co-corresponding authors) ([Paper](https://ieeexplore.ieee.org/abstract/document/9806163), [Code](https://github.com/zm17943/SplitAVG))
- [IEEE CVPR 2022] Rethinking architecture design for tackling data heterogeneity in federated learning. ***Liangqiong Qu***, Yuyin Zhou, Paul Pu Liang, Yingda Xia, Feifei Wang, Ehsan Adeli, Li Fei-Fei, Daniel Rubin. ([Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Qu_Rethinking_Architecture_Design_for_Tackling_Data_Heterogeneity_in_Federated_Learning_CVPR_2022_paper.pdf), [Code](https://github.com/Liangqiong/ViT-FL-main))


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
