---
layout: about
title: About
permalink: /
subtitle: Ph.D. Candidate at Beihang University (BUAA)

profile:
  align: right
  image: luoyuankai.jpg
  image_circular: false # crops the image to make it circular

news: true  # includes a list of news items
# latest_posts: true  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
# services: >
#       <p>555 your office number</p>
#       <p>123 your address street</p>
#       <p>Your City, State 12345</p>

---

Email: luoyk@buaa.edu.cn, yuankluo@polyu.edu.hk

[[Google Scholar](https://scholar.google.com/citations?user=33f_QqAAAAAJ&hl=en)] [[Github](https://github.com/LUOyk1999)] 
<!-- [[OpenReview](https://openreview.net/profile?id=~Yuankai_Luo2)]  -->
<!-- [[CV](https://luoyk1999.github.io/assets/pdf/CV_Yuankai.pdf)] -->

I am a Ph.D. candidate in School of Computer Science and Engineering, Beihang University, supervised by [Prof. Lei Shi](https://leishidata.com/) and a joint Ph.D. student at The Hong Kong Polytechnic University under the supervision of [Prof. Xiao-Ming Wu](https://www4.comp.polyu.edu.hk/~csxmwu/). Before that, I did research supervised by [Veronika Thost](https://mitibmwatsonailab.mit.edu/people/veronika-thost/). Previously, I received the BEng degree in Computer Science and Engineering from Chongqing University of Posts and Telecommunications, in 2021.

My research interests span Graph Neural Network (GNN) research, including architecture design, pre-training strategies, and compression/acceleration:

**GNN Architecture and Analysis**:
- **Unified Framework GNN+ for Reassessing Classic GNNs in General Graph Tasks**: developed **GNN+**, a framework that integrates message passing and well-known regularization techniques like dropout. GNN+ demonstrates that the true potential of classic GNNs has been previously underestimated in both node-level and graph-level tasks, challenging the belief that complex mechanisms are necessary for superior performance in graph models [[NeurIPS 2024](https://openreview.net/forum?id=xkljKdGe4E), [ICML 2025](https://arxiv.org/abs/2502.09263), [ICLR 2025](https://openreview.net/forum?id=PwxYoMvmvy)].
- **Graph Transformers for Specialized Small-Scale Graph Tasks**: designed specialized Graph Transformers architecture tailored for small-scale graph tasks, particularly **directed acyclic graphs** [[NeurIPS 2023](https://openreview.net/forum?id=g49s1N5nmO), [KDD 2023](https://dl.acm.org/doi/abs/10.1145/3580305.3599845)], and graphs with **multi-level structures** [[NeurIPS 2024]](https://openreview.net/forum?id=U4KldRgoph).

**GNN Pre-training**: proposed a graph self-supervised learning framework **based on persistent homology** theory, which effectively captures the multi-scale topological features of graph data [[NeurIPS 2023]](https://openreview.net/forum?id=wEiUGpcr0M). 

**GNN Compression**: introduced vector quantization to compress continuous node embeddings into highly compact (typically 6-15 dimensions), discrete (int4 type), and interpretable node representations—termed **Node IDs** [[ICLR 2025]](https://openreview.net/forum?id=t9lS1lX9FQ).

<!-- **GNN Applications**: applied the developed methodologies to real-world graph tasks, including self-supervised molecular graph learning using persistent homology to improve **molecular property predictions**, especially in scenarios with limited labeled data [[NeurIPS 2023]](https://openreview.net/forum?id=wEiUGpcr0M) and **scholarly impact profiling** through the analysis of self-citation graphs [[KDD 2023]](https://dl.acm.org/doi/abs/10.1145/3580305.3599845). -->