---
title: "DP-MERF: Differentially Private Mean Embeddings with Random Features for Practical Privacy-Preserving Data Generation"
collection: publications
permalink: /publication/2021-dpmerf
excerpt: 'We propose a differentially private data generation paradigm using random feature representations of kernel mean embeddings when comparing the distribution of true data with that of synthetic data. We exploit the random feature representations for two important benefits. First, we require a minimal privacy cost for training deep generative models. This is because unlike kernel-based distance metrics that require computing the kernel matrix on all pairs of true and synthetic data points, we can detach the data-dependent term from the term solely dependent on synthetic data. Hence, we need to perturb the data-dependent term only once and then use it repeatedly during the generator training. Second, we can obtain an analytic sensitivity of the kernel mean embedding as the random features are norm bounded by construction. This removes the necessity of hyper-parameter search for a clipping norm to handle the unknown sensitivity of a generator network. We provide several variants of our algorithm, differentially-private mean embeddings with random features (DP-MERF) to jointly generate labels and input features for datasets such as heterogeneous tabular data and image data. Our algorithm achieves drastically better privacy-utility trade-offs than existing methods when tested on several datasets.'
date: 2021
venue: 'AISTATS2021'
paperurl: 'https://arxiv.org/abs/2002.11603'
citation: 'Harder, F., Adamczewski, K., & Park, M. (2021, March). DP-MERF: Differentially Private Mean Embeddings with RandomFeatures for Practical Privacy-preserving Data Generation. In International Conference on Artificial Intelligence and Statistics (pp. 1819-1827). PMLR.'
---

We propose a method for differentially private data release using random fourier feature Kernel embeddings.

[Arxiv Version](https://arxiv.org/abs/2002.11603)
[AISTATS Version](http://proceedings.mlr.press/v130/harder21a.html)

Bibtex citation: 
<pre>@inproceedings{harder2021dp,
  title={DP-MERF: Differentially Private Mean Embeddings with RandomFeatures for Practical Privacy-preserving Data Generation},
  author={Harder, Frederik and Adamczewski, Kamil and Park, Mijung},
  booktitle={International Conference on Artificial Intelligence and Statistics},
  pages={1819--1827},
  year={2021},
  organization={PMLR}
}
</pre>
