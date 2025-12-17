---
layout: post
title: New article in MNRAS 📃
date: 2025-12-15 10:00:00-0400
inline: false
related_posts: false
---

Cold Dark Matter accounts for most of the matter content of the Universe, and is hence a key ingredient in cosmological simulations. Traditional N-Body simulations discretize the CDM fluid into particles (Diracs in the phase space), leading to inacurracies at small scales. My new article, <a href="https://arxiv.org/abs/2512.11795">Solving the Cosmological Vlasov-Poisson Equations with Physics-Informed Kolmogorov-Arnold Networks</a>, to be published in MNRAS, provides an alternative path to evolve the CDM fluid sheet using neural networks.

<img src="/assets/img/pikan_and_nbody.gif" 
     alt="CDM simulation with PIKAN vs N-body"
     style="width: 100%;" />

In the image above, the PIKAN output is compared to the N-body simulation in the phase space, for a 1D single halo collapse. The CDM sheet (dark line) folds in a spiral pattern. The PIKAN achieves remarkable results, without discretizing the CDM sheet.

The code behind the paper is publicly available in the <a href="https://github.com/nicolas-cerardi/cdm-pikan">cdm-pikan</a> github repo.