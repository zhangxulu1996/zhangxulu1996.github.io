---
title: "Compositional inversion for stable diffusion models"
collection: publications
category: manuscripts
date: 2024-1-1
venue: 'AAAI'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/28565'
citation: 'Xulu Zhang et al., (2024). &quot;Compositional inversion for stable diffusion models.&quot; <i>AAAI 2024</i>.'
---

Inversion methods, such as Textual Inversion, generate personalized images by incorporating concepts of interest provided by user images. However, existing methods often suffer from overfitting issues, where the dominant presence of inverted concepts leads to the absence of other desired concepts. It stems from the fact that during inversion, the irrelevant semantics in the user images are also encoded, forcing the inverted concepts to occupy locations far from the core distribution in the embedding space. To address this issue, we propose a method that guides the inversion process towards the core distribution for compositional embeddings. Additionally, we introduce a spatial regularization approach to balance the attention on the concepts being composed. Our method is designed as a post-training approach and can be seamlessly integrated with other inversion methods. Experimental results demonstrate the effectiveness of our proposed approach in mitigating the overfitting problem and generating more diverse and balanced compositions of concepts in the synthesized images. The source code is available at https://github.com/zhangxulu1996/Compositional-Inversion.


<img src='/images/paper3_fig.jpg'>
