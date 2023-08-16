---
title: "WDAN has been accepted by IEEE T-CSVT!"
date: 2023-02-01T15:34:30-04:00
categories:
  - papers
tags:
  - Journal
  - TCSVT
---

Abstract:
Deep neural networks usually depend on substantial labeled data and suffer from poor generalization to new domains. Domain adaptation can be used to resolve these issues, using a classifier trained with a label-rich source and transferred to a label-scarce target domain. Traditional domain adaptation adopts the close-set assumption that both domains share the same classes. However, real-world applications operate in an open-set scenario where target domains have private categories. This aspect is considered by open-set domain adaptation (OSDA). Nevertheless, current OSDA benchmarks lack clear definitions of semantic classes that are at the core of the open-set concept. In this study, we propose fine-grained visual categorization (FGVC) datasets containing specific descriptions of semantic classes as a solution, introducing the new setting named fine-grained OSDA. Owing to the entanglement among FGVC, unknown class recognition, and domain adaptation, fine-grained OSDA is a challenging task. For this reason, we designed a weighted discriminative adversarial network with dual classifiers (WDAN). It utilizes a selective transformer encoder with overlapping patches and supervised contrastive learning to extract features suitable for FGVC, adversarial training with domain-specific discriminative information to recognize target-private classes, and a weighted conditional domain discriminator to learn domain-invariant features for domain adaptation. Extensive experiments on five benchmarks, including one newly built, demonstrated that WDAN outperforms state-of-the-art methods. This work fills the existing gap in benchmarks for fine-grained OSDA, promoting future developments of real-world applications.

Check out the [paperPage][paperPage] for details if you are interested.

[paperPage]: [https://jekyllrb.com/docs/home](https://ieeexplore.ieee.org/abstract/document/10054088)
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
