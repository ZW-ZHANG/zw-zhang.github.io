---
title: "Billion-scale Network Embedding with Iterative Random Projection"
collection: publications
permalink: /publication/2018-08-Billion-scale-Network-Embedding-with-Iterative-Random-Projection
excerpt: 'Key words: network embedding, billion-scale, random projection, distributed algorithm, dynamic networks'
date: 2018-08-01
venue: ICDM
paperurl: 'https://zw-zhang.github.io/files/2018_ICDM_RandNE.pdf'
citation: 'Zhang, Ziwei, et al. "Billion-scale Network Embedding with Iterative Random Projection." Data Mining (ICDM), 2018 IEEE International Conference on. IEEE, 2018.'
---
Network embedding has attracted considerable research
attention recently. However, the existing
methods are incapable of handling billion-scale
networks, because they are computationally expensive
and, at the same time, difficult to be accelerated
by distributed computing schemes. 

To address
these problems, we propose RandNE, a novel and
simple billion-scale network embedding method.
Specifically, we propose a Gaussian random projection
approach to map the network into a lowdimensional
embedding space while preserving the
high-order proximities between nodes. To reduce
the time complexity, we design an iterative projection
procedure to avoid the explicit calculation
of the high-order proximities. Theoretical analysis
shows that our method is extremely efficient, and
friendly to distributed computing schemes without
any communication cost in the calculation. We
demonstrate the efficacy of RandNE over state-ofthe-
art methods in network reconstruction and link
prediction tasks on multiple datasets with different
scales, ranging from thousands to billions of nodes
and edges.

Code is available [here](https://github.com/ZW-ZHANG/RandNE).

Slide is available [here](https://zw-zhang.github.io/files/2018_ICDM_Slides.pdf).

Recommended citation: 
```
@inproceedings{zhang2018billion,
  title={Billion-scale Network Embedding with Iterative Random Projection},
  author={Zhang, Ziwei and Cui, Peng and Li, Haoyang and Wang, Xiao and Zhu, Wenwu},
  booktitle={Data Mining (ICDM), 2018 IEEE International Conference on},
  year={2018},
  organization={IEEE}
}
```