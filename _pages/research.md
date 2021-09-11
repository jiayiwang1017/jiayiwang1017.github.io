---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

<!---
My research falls into two main areas: understanding patterns of rebel behavior before, during, and after civil conflict, and developing new tools to improve the study of peace and conflict. One strand of research explores how the territories that ethnic groups inhabit shape rebel group formation and condition their relationship with the state. This interest in rebel behavior also informs projects on the evolution of government repression and rebel killings of civilians over the course of a conflict.

My other main research agenda uses advanced methods to allow us to ask new questions in the study of peace and conflict. One project uses Bayesian item response theory to measure the strength of peace agreements as a latent variable and free researchers from post-treatment bias caused by using the duration of agreements as a proxy for their strength. In another project, I use visual imagery contained in Salafi jihadist propaganda videos to detect similiarties in videos produced by different groups, allowing researchers to estimate collaboration networks within a broader clandestine movement. Other work uses over two billion observations of international trade data to develop new measures of economic interdependence and methods to detect disruptions of regular economic exchange between states.
-->

<!--
Overview
===
My current research falls into two main areas. 

First, I develop new methodologies and theories for statistical problems with functional data structure, especially when the data is sparsely observed and  multi-dimensional. Second, I explore robust estimators with data involving unknow missing structures,  such as causal inference, matrix completion, and reinforcement learning. 
-->

## Research Interest

- Functional Data
- Low-rank Modeling
- Causal Inference
- Reinforcement Learning


## Preprints


- **J. Wang**, R. K. W. Wong, S. Yang and K. C. G. Chan.  "**Estimation of Partially Conditional Average Treatment Effect by Hybrid Kernel-covariate Balancing**", submitted, 2021.

  [arXiv](https://arxiv.org/abs/2103.03437){: .btn--research} 



## Publication


- **J. Wang**, R. K. W. Wong, X. Mao and K. C. G. Chan. (2021+). "**Matrix Completion with Model-free Weighting**". International Conference on Machine Learning (ICML).

  [arXiv](https://arxiv.org/abs/2106.05850){: .btn--research}  [Code](https://github.com/jiayiwang1017/MC-weighting-code){: .btn--research}


- **J. Wang**, R. K. W. Wong and X. Zhang (2021+). "**Low-rank Covariance Function Estimation for Multidimensional Functional Data**". Journal of the American Statistical Association.
  - ASA Section on Nonparametric Statistics Student Paper Award (2020)

  [Journal](https://www.tandfonline.com/doi/full/10.1080/01621459.2020.1820344){: .btn--research} [arXiv](https://arxiv.org/abs/2008.12919){: .btn--research}  [Code](https://github.com/jiayiwang1017/mfdacov-code){: .btn--research}






<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
