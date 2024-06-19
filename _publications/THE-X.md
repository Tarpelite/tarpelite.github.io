---
title: "The-X: Privacy-preserving transformer inference with homomorphic encryption"
collection: publications
permalink: /publication/THE-X
excerpt: 'The first work to protect Transformers in HE ways.'
date: 2022-05-31
venue: 'ACL findings 2022'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://aclanthology.org/2022.findings-acl.277.pdf'
citation: 'THE-X: Privacy-Preserving Transformer Inference with Homomorphic Encryption (Chen et al., Findings 2022)'
---

As more and more pre-trained language models adopt on-cloud deployment, the privacy issues grow quickly, mainly for the exposure of plain-text user data (e.g., search history, medical record, bank account). Privacy-preserving inference of transformer models is on the demand of cloud service users. To protect privacy, it is an attractive choice to compute only with ciphertext in homomorphic encryption (HE). However, enabling pre-trained models inference on ciphertext data is difficult due to the complex computations in transformer blocks, which are not supported by current HE tools yet. In this work, we introduce THE-X, an approximation approach for transformers, which enables privacy-preserving inference of pre-trained models developed by popular frameworks. THE-X proposes a workflow to deal with complex computation in transformer networks, including all the non-polynomial functions like GELU, softmax, and LayerNorm. Experiments reveal our proposed THE-X can enable transformer inference on encrypted data for different downstream tasks, all with negligible performance drop but enjoying the theory-guaranteed privacy-preserving advantage.
