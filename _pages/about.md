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
[[Google Scholar](https://scholar.google.com/citations?user=33f_QqAAAAAJ&hl=en)] [[Github](https://github.com/LUOyk1999)] [Email: yuankailuo@nju.edu.cn] 
<!-- [[OpenReview](https://openreview.net/profile?id=~Yuankai_Luo2)]  -->
<!-- [[CV](https://luoyk1999.github.io/assets/pdf/CV_Yuankai.pdf)] -->

I am currently an Assistant Professor at the [School of Artificial Intelligence](https://ai.nju.edu.cn/), Nanjing University (NJU). I received my Ph.D. degree from the School of Computer Science and Engineering at Beihang University, where I was supervised by [Prof. Lei Shi](https://leishidata.com/) and jointly trained at The Hong Kong Polytechnic University under the supervision of [Prof. Xiao-Ming Wu](https://www4.comp.polyu.edu.hk/~csxmwu/). Before that, I did research supervised by [Veronika Thost](https://scholar.google.com/citations?user=TyScgJ0AAAAJ/).

My research asks a central question: **how can we make models for complex structured data simpler, more efficient, and more reliable?** Driven by the philosophy of "Simplicity," my work has evolved from efficient structural representation and architecture optimization toward real-world embodied intelligence, where lightweight deployment is essential.

**1. Embodied Intelligence: Lightweight On-Device Deployment**

- **VLA / VLN**: our primary focus is building lightweight and scalable embodied agents for robotic manipulation and navigation. [**SimVLA**](https://arxiv.org/abs/2602.18224) provides a streamlined VLA baseline by decoupling perception from control and using a standard training recipe, flow matching, and self-attention. [**CORAL**](https://arxiv.org/abs/2603.09298) extends this foundation to scalable multi-task deployment through lightweight, parameter-isolated LoRA experts and dynamic instruction-based routing, with minimal storage cost and zero additional inference overhead [[IROS 2026](https://arxiv.org/abs/2603.09298)].

- **Generation-Aware On-Device Detection and Segmentation**: develop unified models that combine visual generation with perception to better handle rare and challenging corner cases. In particular, we explore jointly performing image inpainting and detection or segmentation prediction, allowing models to recover missing visual evidence while recognizing targets efficiently on drones and robotic platforms.

- **Multimodal Reasoning and Real-Time Video Understanding**: study efficient multimodal reasoning over continuous video streams from surveillance cameras, drones, and embodied agents. Our goal is to enable real-time understanding of evolving scenes, events, and agent interactions from both third-person and egocentric perspectives.


**2. Efficient Structural Representation and Architecture Optimization**

- **Systematic Architecture Refinement (ModernGNN / GNN+)**: revisited classic GNNs through a systematic integration of message passing, residual connections, normalization, and regularization, establishing strong and simple baselines for node- and graph-level learning [[NeurIPS 2024](https://openreview.net/forum?id=xkljKdGe4E), [ICML 2025](https://arxiv.org/abs/2502.09263), [ICLR 2025](https://openreview.net/forum?id=PwxYoMvmvy)].

- **Structural Encoding and Graph Transformers**: developed compact, discrete, and interpretable **Node IDs** through vector quantization [[ICLR 2025]](https://openreview.net/forum?id=t9lS1lX9FQ), and designed Graph Transformers for complex topologies, including DAGs [[NeurIPS 2023]](https://openreview.net/forum?id=g49s1N5nmO) and multi-level structures [[NeurIPS 2024]](https://openreview.net/forum?id=U4KldRgoph). These methods have been applied to molecular property prediction [[NeurIPS 2023]](https://openreview.net/forum?id=wEiUGpcr0M) and scholarly impact profiling [[KDD 2023]](https://dl.acm.org/doi/abs/10.1145/3580305.3599845).

- **Graph Generation**: proposed **SimGFM**, a simplified discrete flow matching framework that uses endpoint-focused scheduling and safe projection to reduce graph generation from hundreds of sampling steps to fewer than ten [[ICML 2026](https://openreview.net/forum?id=Z3xgDd5B2L)].