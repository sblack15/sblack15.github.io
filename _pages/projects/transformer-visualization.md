---
layout: archive
permalink: /projects/transformer-visualization/
author_profile: true
---

<div style="text-align: center; margin-top: 20px;">
  <h1 style="margin-bottom: 10px;">Visualizing Paired Image Similarity in Transformer Networks</h1>
</div>

<div style="text-align: center;">
  <div style="display: flex; justify-content: center; margin: 0;">
    <ul style="list-style: none; padding: 0; display: flex; gap: 15px; justify-content: center; margin: 0;">
      <li><h3 style="margin: 0;">Samuel Black</h3></li>
      <li><h3 style="margin: 0;">Abby Stylianou</h3></li>
      <li><h3 style="margin: 0;">Robert Pless</h3></li>
      <li><h3 style="margin: 0;">Richard Souvenir</h3></li>
    </ul>
  </div>
  <h4 style="margin-top: 10px;">Published at WACV 2022</h4>
</div>

<div style="display: flex; justify-content: center; margin-top: 5px;">
  <ul style="list-style: none; padding: 0; display: flex; gap: 25px; justify-content: center;">
    <li><a href="https://openaccess.thecvf.com/content/WACV2022/papers/Black_Visualizing_Paired_Image_Similarity_in_Transformer_Networks_WACV_2022_paper.pdf" target="_blank">Paper</a></li>
    <li><a href="https://github.com/vidarlab/xformer-paired-viz" target="_blank">Code</a></li>
    <li><a href="https://www.youtube.com/watch?v=kYO0p-jW4YE" target="_blank">Talk</a></li>
  </ul>
</div>

<img src="/research/images/transformers_viz.png" alt="transformers visualization" width="900"/>

Transformer architectures have shown promise for a wide range of computer vision tasks, including image embedding. As was the case with convolutional neural networks and other models, explainability of the predictions is a key concern, but visualization approaches tend to be architecture-specific. In this work, we introduce a new method for producing interpretable visualizations that, given a pair of images encoded with a Transformer, show which regions contributed to their similarity. Additionally, for the task of image retrieval, we compare the performance of Transformer and ResNet models of similar capacity and show that while they have similar performance in aggregate, the retrieved results and the visual explanations for those results are quite different.

Examples of paired similarity maps generated with our method:

<img src="/research/images/xformer-viz-examples.png" alt="transformers visualization" width="900"/>

<div style="border: 1px solid #ccc; padding: 15px; margin-top: 20px; background-color: #f9f9f9;">
  <strong>BibTeX Citation:</strong>
  <pre style="font-family: monospace; white-space: pre-wrap; background: #f4f4f4; padding: 10px; border-radius: 5px; font-size: 0.7em;">
@inproceedings{black2022visualizing,
  title={Visualizing Paired Image Similarity in Transformer Networks},
  author={Black, Samuel and Stylianou, Abby and Pless, Robert and Souvenir, Richard},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={3164--3173},
  year={2022}
  }
  </pre>
</div>