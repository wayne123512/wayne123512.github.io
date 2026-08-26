---
title: 'Target Mirror Descent: A Unifying Framework for Solving Monotone Variational Inequalities'
authors:
- admin
- Can Kizilkale
- Murat Arcak
date: '2026-06-11'
featured: true
abstract: 'It is well known that mirror descent may diverge or cycle on merely monotone variational inequalities. In this paper, we propose Target Mirror Descent (TMD), a unified framework that stabilizes monotone flows via a target point correction mechanism in the dual update. By appropriate design choices, the TMD framework recovers the proximal point algorithm, extragradient methods, splitting methods, Brown-von Neumann-Nash dynamics, forward-backward-forward dynamics, and discounted mirror descent as special instances. Thus, we establish a unified perspective on these landmark algorithms and their convergence. Beyond unification, we leverage the TMD framework to correct an equilibrium misalignment in discounted mirror descent and to generalize its higher-order extension beyond interior solutions. Moreover, a key structural feature of TMD is the explicit decoupling of the mirror map from the target determination, which enables geometric ensembles: multiple TMD instances solve the same problem in parallel using distinct mirror maps, while sharing a common dual update. We show that such an ensemble rigorously reduces to a single TMD with a synthesized mirror map, and thus inherits these convergence guarantees.'

publication_types:
- article-journal
publication: '*IEEE Control Systems Letters*'

url_slides: 'slides.pdf'

links:
- name: arXiv
  url: https://arxiv.org/abs/2604.18813

tags:
- Optimization
- Multi-agent Systems
- Game Theory
---
