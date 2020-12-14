---
title: "The Zero Resource Speech Benchmark 2021: Metrics and baselines for unsupervised spoken language modeling"
collection: publications
permalink: /publication/2020-neurips-paper-zr21
excerpt: ''
date: 2020-11-23
venue: ' NeurIPS Workshop on Self-Supervised Learning for Speech and Audio Processing'
paperurl: 'https://maureendss.github.io/files/2020_neurips.pdf'
citation: 'Nguyen, T. A.*, **de Seyssel, M.\***, Rozé, P., Rivière, M., Kharitonov, E., Baevski, A., Dunbar, E., and Dupoux,E. (2020). The zero resource speech benchmark 2021: Metrics and baselines for unsupervised spoken language modeling. <i>Neurips Workshop on Self-Supervised Learning for Speech and Audio Processing</i>.'
---
We introduce a new unsupervised task, spoken language modeling: the learning of linguistic representations from raw audio signals without any labels, along with the Zero Resource Speech Benchmark 2021: a suite of 4 black-box, zero-shot metrics probing for the quality of the learned models at 4 linguistic levels: phonetics, lexicon, syntax and semantics. We present the results and analyses of a composite baseline made of the concatenation of three unsupervised systems: self-supervised contrastive representation learning (CPC), clustering (k-means) and language modeling (LSTM or BERT). The language models learn on the basis of the pseudo-text derived from clustering the learned representations. This simple pipeline shows better than chance performance on all four metrics, demonstrating the feasibility of spoken language modeling from raw speech. It also yields worse performance compared to text-based ‘topline’ systems trained on the same data, delineating the space to be explored by more sophisticated end-to-end models.

*\*: Equal contribution as first author*

[Download paper here](https://arxiv.org/pdf/2011.11588.pdf)

Recommended citation: Nguyen, T. A., de Seyssel, M., Rozé, P., Rivière, M., Kharitonov, E., Baevski, A., Dunbar, E., and Dupoux,E. (2020). The zero resource speech benchmark 2021: Metrics and baselines for unsupervised spoken language modeling. *Neurips Workshop on Self-Supervised Learning for Speech and Audio Processing*.
