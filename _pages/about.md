---
layout: about
title: About
permalink: /
subtitle: Assistant Professor at Nanjing University

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
Email: yuankailuo@nju.edu.cn

[[Google Scholar](https://scholar.google.com/citations?user=33f_QqAAAAAJ&hl=en)] [[Github](https://github.com/LUOyk1999)] 
<!-- [[OpenReview](https://openreview.net/profile?id=~Yuankai_Luo2)]  -->
<!-- [[CV](https://luoyk1999.github.io/assets/pdf/CV_Yuankai.pdf)] -->

I am currently an Assistant Professor at the [School of Artificial Intelligence](https://ai.nju.edu.cn/), Nanjing University (NJU). I received my Ph.D. degree from the School of Computer Science and Engineering at Beihang University, where I was supervised by [Prof. Lei Shi](https://leishidata.com/) and jointly trained at The Hong Kong Polytechnic University under the supervision of [Prof. Xiao-Ming Wu](https://www4.comp.polyu.edu.hk/~csxmwu/). Before that, I did research supervised by [Veronika Thost](https://scholar.google.com/citations?user=TyScgJ0AAAAJ/).

Driven by the philosophy of "Simplicity through First Principles," my research focuses on improving the efficiency and scalability of AI systems. My work has evolved from optimizing structural representation frameworks to developing efficient generative frameworks for Embodied AI and Scientific Discovery.

**ModernGNN: Efficient Structural Representation**:
- **Systematic Architecture Refinement**: developed **ModernGNN (GNN+)**, a framework that integrates message passing and well-known regularization techniques like dropout. GNN+ demonstrates that the true potential of classic GNNs has been previously underestimated in both node-level and graph-level tasks, challenging the belief that complex mechanisms are necessary for superior performance in graph models [[NeurIPS 2024](https://openreview.net/forum?id=xkljKdGe4E), [ICML 2025](https://arxiv.org/abs/2502.09263), [ICLR 2025](https://openreview.net/forum?id=PwxYoMvmvy)].

- **Neural Compression**: introduced vector quantization to compress continuous node embeddings into highly compact (typically 6-15 dimensions), discrete (int4 type), and interpretable node representations—termed **Node IDs** [[ICLR 2025]](https://openreview.net/forum?id=t9lS1lX9FQ).

- **Specialized Architectures & Applications**: designed Graph Transformers for complex topologies, including DAGs [[NeurIPS 2023]](https://openreview.net/forum?id=g49s1N5nmO) and multi-level structures [[NeurIPS 2024]](https://openreview.net/forum?id=U4KldRgoph). Applied these methods to practical tasks, such as molecular property prediction using persistent homology [[NeurIPS 2023]](https://openreview.net/forum?id=wEiUGpcr0M) and scholarly impact profiling [[KDD 2023]](https://dl.acm.org/doi/abs/10.1145/3580305.3599845).

**Sim-Series: Efficient Generative Frameworks**

- **Robotic Action Generation ([SimVLA](https://arxiv.org/abs/2602.18224))**: established a efficient Vision-Language-Action baseline for robotic manipulation by decoupling perception from control. It demonstrates that a streamlined architecture—centered on a standardized training recipe, standard flow matching, and a standard self-attention head—can perform robustly across diverse manipulation tasks.

- **Graph Generation ([SimGFM](https://openreview.net/forum?id=eCftYujQkK))**: proposed a simplified Discrete Flow Matching framework for graph generation. By utilizing an endpoint-focused scheduler and eliminating task-specific heuristics, the approach reduces the required sampling steps for structural generation from hundreds to fewer than ten.