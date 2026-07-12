---
title:          "Self-conditioned Flow Map Language Models via Fixed-point Flows"
anchor:         sc-fmlm
date:           2026-07-01 00:01:00 +0900
selected:       true
# pub:            "None"
underpub:       "Preprint."
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date:       "2026"
semantic_scholar_id: dd2ab50139b137a3ba0624afd32e209bf043949f # use this to retrieve citation count
abstract: >-
  Self-conditioning is a core technique that enhances continuous flow-based language models, where the model learns to denoise generated text by conditioning on its own denoising estimate. While empirically successful, its performance improvements are poorly understood. Moreover, there is growing interest in the use of few-step generators based on flow maps, for which how to leverage self-conditioning is unclear. Here, we show that flow language models with self-conditioning solve a fixed-point iteration that bootstraps the performance of the learned denoiser. We use this viewpoint to formulate <strong>fixed-point flows</strong>, a two-dimensional class of self-conditioned flows, where the first dimension represents the flow process and the second represents the fixed-point iteration. We show that fixed-point flows define valid flow maps, and show that they can be distilled from self-conditioned flow models by compressing both fixed-point iterations and the flow process, the former with fixed-point distillation and the latter with flow map distillation. Our resulting flow map language model, <strong>FMLM⋆</strong>, outperforms state-of-the-art self-conditioned models and few-step models in one- and few-step generation on OpenWebText.
cover:          /assets/images/covers/sc_fmlm.png
authors:
  - Jaehoon Yoo*
  - Wonjung Kim*
  - Floor Eijkelboom
  - Chanhyuk Lee
  - Nicholas M. Boffi
  - Seunghoon Hong†
  - Jinwoo Kim†
links:
  Paper: https://arxiv.org/abs/2607.00714
  Code: https://github.com/Ugness/self-conditioned-fmlm
---
