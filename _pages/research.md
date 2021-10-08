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

## Overview
I am broadly interested in the field of nonparametric statistics and machine learning. The overarching theme of my research is on developing novel statistical and machine learning methods that are motivated by real-world problems and supported by rigorous theory. One of my current focuses is the statistical problems that involve functional data. On the one hand, I develop methodology and theory for functional data analysis with modern data challenges such as multidimensionality and sparse design. On the other hand, I am interested in the applications of functional data in other statistical areas, such as causal inference. Another branch of my current research is handling imperfect data where observations are partially missing or collected under an undesirable distribution. In particular, I study such problems in different areas such as causal inference, matrix completion, and reinforcement learning.





## Research Interests

- Functional Data
- Low-rank Modeling
- Missing Data
- Causal Inference
- Reinforcement Learning






<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
