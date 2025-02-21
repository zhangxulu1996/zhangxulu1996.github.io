---
title: "Identifying the kind behind SMILES—anatomical therapeutic chemical classification using structure-only representations"
collection: publications
category: manuscripts
date: 2022-1-1
venue: 'Briefings in Bioinformatics'
paperurl: 'https://academic.oup.com/bib/article/23/5/bbac346/6677124'
citation: 'Yi Cao, Zhen-Qun Yang, Xu-Lu Zhang, et al., (2022). &quot;Identifying the kind behind SMILES—anatomical therapeutic chemical classification using structure-only representations.&quot; <i>Briefings in Bioinformatics</i>.'
---

Anatomical Therapeutic Chemical (ATC) classification for compounds/drugs plays an important role in drug development and basic research. However, previous methods depend on interactions extracted from STITCH dataset which may make it depend on lab experiments. We present a pilot study to explore the possibility of conducting the ATC prediction solely based on the molecular structures. The motivation is to eliminate the reliance on the costly lab experiments so that the characteristics of a drug can be pre-assessed for better decision-making and effort-saving before the actual development. To this end, we construct a new benchmark consisting of 4545 compounds which is with larger scale than the one used in previous study. A light-weight prediction model is proposed. The model is with better explainability in the sense that it is consists of a straightforward tokenization that extracts and embeds statistically and physicochemically meaningful tokens, and a deep network backed by a set of pyramid kernels to capture multi-resolution chemical structural characteristics. Its efficacy has been validated in the experiments where it outperforms the state-of-the-art methods by 15.53% in accuracy and by 69.66% in terms of efficiency. We make the benchmark dataset, source code and web server open to ease the reproduction of this study.


<img src='/images/paper2_fig.jpg'>
