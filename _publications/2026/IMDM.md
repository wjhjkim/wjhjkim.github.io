---
title:          "Infinite Mask Diffusion for Few-Step Distillation"
date:           2026-05-15 00:01:00 +0900
selected:       true
pub:            "ICML"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"
# semantic_scholar_id: 59d257bf4108b8915d7ba406d517e6ce4f11d51a # use this to retrieve citation count
abstract: >-
  Masked Diffusion Models (MDMs) have emerged as a promising alternative to autoregressive models in language modeling, offering the advantages of parallel decoding and bidirectional context processing within a simple yet effective framework. Specifically, their explicit distinction between masked tokens and data allows their simple framework and effective conditional generation. However, MDMs typically require many sampling iterations due to factorization errors stemming from simultaneous token updates. We observe that a theoretical lower bound of the factorization error exists, which standard MDMs cannot reduce due to their use of a deterministic single-state mask. In this paper, we propose the <strong>Infinite Mask Diffusion Model (IMDM)</strong>, which introduces a stochastic infinite-state mask to mitigate the theoretical bound while directly inheriting the benefits of MDMs, including the compatibility with pre-trained weights. We empirically demonstrate that MDM fails to perform few-step generation even in a simple synthetic task due to the factorization error bound, whereas IMDM can find an efficient solution for the same task. Finally, when equipped with appropriate distillation methods, IMDM surpasses existing few-step distillation methods at small step counts on LM1B and OpenWebText.
cover:          /assets/images/covers/imdm.png
authors:
  - Jaehoon Yoo*
  - Wonjung Kim*
  - Chanhyuk Lee
  - Seunghoon Hong
links:
  Paper: https://arxiv.org/abs/2605.10518
  Code: https://github.com/Ugness/IMDM
  Project Page: https://Ugness.github.io/official_imdm
---
