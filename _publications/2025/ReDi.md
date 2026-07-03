---
title:          "ReDi: Rectified Discrete Flow"
date:           2025-07-12 00:01:00 +0900
selected:       true
pub:            "NeurIPS"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"
semantic_scholar_id: e80b885174c946932e54d9de54f2eff22771c4d2  # use this to retrieve citation count
abstract: >-
  Discrete Flow-based Models (DFMs) are powerful generative models for high-quality discrete data but typically suffer from slow sampling speeds due to their reliance on iterative decoding processes. This reliance on a multi-step process originates from the factorization approximation of DFMs, which is necessary for handling high-dimensional data. In this paper, we analyze the factorization approximation error using Conditional Total Correlation (TC), and reveal its dependence on the coupling. To address the challenge of efficient few-step generation, we propose <strong>Rectified Discrete Flow (ReDi)</strong>, a novel iterative method that reduces the underlying factorization error (measured as Conditional TC) by rectifying the coupling between source and target distributions. We theoretically prove that each ReDi step guarantees a monotonic decreasing Conditional TC, ensuring its convergence. Empirically, ReDi significantly reduces Conditional TC and enables few-step generation. Moreover, we demonstrate that the rectified couplings are well-suited for training efficient one-step models on image generation. ReDi offers a simple and theoretically grounded approach for tackling the few-step challenge, providing a new perspective on efficient discrete data synthesis.
cover:          /assets/images/covers/redi.png
authors:
  - Jaehoon Yoo
  - Wonjung Kim
  - Seunghoon Hong
links:
  Paper: https://arxiv.org/abs/2507.15897
  Code: https://github.com/Ugness/ReDi
  Project Page: https://Ugness.github.io/official_redi
---
