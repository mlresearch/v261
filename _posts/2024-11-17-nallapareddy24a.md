---
abstract: Translation elongation plays an important role in regulating protein concentrations
  in the cell, and dysregulation of this process has been linked to several human
  diseases. In this study, we use data from ribo-seq experiments to model ribosome
  densities, and in turn, predict the speed of translation. The proposed method, RiboGL,
  combines graph and recurrent neural networks to account for both graph and sequence-based
  features. The model takes a graph representing the secondary structure of the mRNA
  sequence as input, which incorporates both sequence and structural codon neighbors.
  In our experiments, RiboGL greatly outperforms the state-of-the-art RiboMIMO model
  for ribosome density prediction. We also conduct ablation studies to justify the
  design choices made in building the pipeline. Additionally, we use gradient-based
  interpretability to understand how the codon context and the structural neighbors
  affect the ribosome density at the A-site. By individually analyzing the genes in
  the dataset, we elucidate how structural neighbors could also potentially play a
  role in defining the ribosome density. Importantly, since these neighbors can be
  far away in the sequence, a recurrent model alone could not easily extract this
  information. This study lays the foundation for understanding how the mRNA secondary
  structure can be exploited for ribosome density prediction, and how in the future
  other graph modalities such as features from the nascent polypeptide can be used
  to further our understanding of translation in general.
title: Towards improving full-length ribosome density prediction by bridging sequence
  and graph-based representations
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nallapareddy24a
month: 0
tex_title: Towards improving full-length ribosome density prediction by bridging sequence
  and graph-based representations
firstpage: 38
lastpage: 52
page: 38-52
order: 38
cycles: false
bibtex_author: Nallapareddy, Mohan Vamsi and Craighero, Francesco and Gobet, C\'edric
  and Naef, Felix and Vandergheynst, Pierre
author:
- given: Mohan Vamsi
  family: Nallapareddy
- given: Francesco
  family: Craighero
- given: Cédric
  family: Gobet
- given: Felix
  family: Naef
- given: Pierre
  family: Vandergheynst
date: 2024-11-17
address:
container-title: Proceedings of the 19th Machine Learning in Computational Biology
  meeting
volume: '261'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 11
  - 17
pdf: https://raw.githubusercontent.com/mlresearch/v261/main/assets/nallapareddy24a/nallapareddy24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
