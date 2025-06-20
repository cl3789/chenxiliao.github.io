---
title: "Unsupervised learning reveals interpretable latent representations for translucency perception"
collection: publications
category: manuscripts
permalink: /publication/unsupervised_learning_translucency
excerpt: 'We developed an deep image generation network to synthesize realistic translucent appearances from unlabeled data and learn a layer-wise latent representation that captures human translucency perception. '
date: 2023-02-08
venue: 'PLOS Computational Biology'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010878'
citation: 'Liao, C., Sawayama, M., & Xiao, B. (2023). Unsupervised learning reveals interpretable latent representations for translucency perception. PLOS Computational Biology, 19(2), e1010878.'
---

Translucency is an essential visual phenomenon, facilitating our interactions with the environment. Perception of translucent materials (i.e., materials that transmit light) is challenging to study due to the high perceptual variability of their appearance across different scenes. We present the first image-computable model that can predict human translucency judgments based on unsupervised learning from natural photographs of translucent objects. We train a deep image generation network to synthesize realistic translucent appearances from unlabeled data and learn a layer-wise latent representation that captures the statistical structure of images at multiple spatial scales. By manipulating specific layers of latent representation, we can independently modify certain visual attributes of the generated object, such as its shape, material, and color, without affecting the others. Particularly, we find the middle-layers of the latent space, which represent mid-to-low spatial scale features, can predict human perception. In contrast, the pixel-based embeddings from dimensionality reduction methods (e.g., t-SNE) do not correlate with perception. Our results suggest that scale-specific representation of visual information might be crucial for humans to perceive materials. We provide a systematic framework to discover perceptually relevant image features from natural stimuli for perceptual inference tasks and therefore valuable for understanding both human and computer vision.

