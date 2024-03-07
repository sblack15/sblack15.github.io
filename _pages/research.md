---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Multi-View Classification With Hybrid Fusion and Mutual Distillation</h2>
<img src="images/mvh.png" alt="multi-view hybrid" width="900"/>

Multi-view classification problems are common in medical image analysis, forensics, and other domains where problem queries involve multi-image input. Existing multi-view classification methods are often tailored to a specific task. In this work, we repurpose off-the-shelf Hybrid CNN-Transformer networks for multi-view classification with either structured or unstructured views. Our approach incorporates a novel fusion scheme, mutual distillation, and minimal additional parameters. We demonstrate the effectiveness and generalization capability of our approach, MV-HFMD, on multiple multi-view classification tasks and show that it outperforms other multi-view approaches, even task-specific methods. [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Black_Multi-View_Classification_Using_Hybrid_Fusion_and_Mutual_Distillation_WACV_2024_paper.pdf) [Code](https://github.com/vidarlab/multi-view-hybrid)

<h2>Visualizing Paired Image Similarity in Transformer Networks</h2>
<img src="images/transformers_viz.png" alt="transformers visualization" width="900"/>

Transformer architectures have shown promise for a wide range of computer vision tasks, including image embedding. As was the case with convolutional neural networks and other models, explainability of the predictions is a key concern, but visualization approaches tend to be architecture-specific. In this work, we introduce a new method for producing interpretable visualizations that, given a pair of images encoded with a Transformer, show which regions contributed to their similarity. Additionally, for the task of image retrieval, we compare the performance of Transformer and ResNet models of similar capacity and show that while they have similar performance in aggregate, the retrieved results and the visual explanations for those results are quite different. [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Black_Visualizing_Paired_Image_Similarity_in_Transformer_Networks_WACV_2022_paper.pdf) [Code](https://github.com/vidarlab/xformer-paired-viz)

<h2>Evaluation of Inpainting and Augmentation for Censored Image Queries</h2>
<table style="border-collapse: collapse; border: none;">
  <tr>
    <!-- Image cell -->
    <td style="border: none;">
    <img src="images/inpainting.png" alt="IJCV teaser" width="5000"/>
    </td>
    <td style="border: none; font-size: 18px;">
    Images can be censored by masking the region(s) of interest with a solid color or pattern. When a censored image is used for classification or matching, the mask itself may impact the results. Recent work in image inpainting and data augmentation provide two different approaches for dealing with censored images. In this work, we perform an extensive evaluation of these methods to understand if the impact of censoring can be mitigated for image classification and retrieval. Results indicate that modern learning-based inpainting approaches outperform augmentation strategies and that metrics typically used to evaluate inpainting performance (e.g., reconstruction accuracy) do not necessarily correspond to improved classification or retrieval, especially in the case of person-shaped masked regions. <a href="https://link.springer.com/article/10.1007/s11263-020-01403-1" target="_blank">Paper</a> <a href="https://github.com/sblack15/CensoredImageQueries" target="_blank">Code</a>
    </td>
  </tr>
</table>