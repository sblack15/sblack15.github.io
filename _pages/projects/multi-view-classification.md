---
layout: archive
permalink: /projects/multi-view-classification/
author_profile: true

---
<div style="text-align: center; margin-top: 20px;">
  <h1 style="margin-bottom: 10px;">Multi-view Classification Using Hybrid Fusion and Mutual Distillation</h1>
</div>

<div style="text-align: center;">
  <div style="display: flex; justify-content: center; margin: 0;">
    <ul style="list-style: none; padding: 0; display: flex; gap: 15px; justify-content: center; margin: 0;">
      <li><h3 style="margin: 0;">Samuel Black</h3></li>
      <li><h3 style="margin: 0;">Richard Souvenir</h3></li>
    </ul>
  </div>
  <h4 style="margin-top: 10px;">Published at WACV 2024</h4>
</div>
<div style="display: flex; justify-content: center; margin-top: 5px;">
  <ul style="list-style: none; padding: 0; display: flex; gap: 25px; justify-content: center;">  <li><a href="https://openaccess.thecvf.com/content/WACV2024/papers/Black_Multi-View_Classification_Using_Hybrid_Fusion_and_Mutual_Distillation_WACV_2024_paper.pdf" target="_blank">Paper</a></li>
  <li><a href="https://github.com/vidarlab/multi-view-hybrid" target="_blank">Code</a></li>
  <li><a href="https://openaccess.thecvf.com/content/WACV2024/supplemental/Black_Multi-View_Classification_Using_WACV_2024_supplemental.pdf" target="_blank">Supplemental</a></li>
  <li><a href="https://www.youtube.com/watch?v=DKUHhhe9hrw" target="_blank">Talk</a></li>
</ul>
</div>

<img src="/research/images/mvh.png" alt="multi-view hybrid" width="900"/>

Multi-view classification problems are common in medical image analysis, forensics, and other domains where problem queries involve multi-image input. Existing multi-view classification methods are often tailored to a specific task. In this work, we repurpose off-the-shelf Hybrid CNN-Transformer networks for multi-view classification with either structured or unstructured views. Our approach incorporates a novel fusion scheme, mutual distillation, and minimal additional parameters. We demonstrate the effectiveness and generalization capability of our approach, MV-HFMD, on multiple multi-view classification tasks and show that it outperforms other multi-view approaches, even task-specific methods.

<div style="border: 1px solid #ccc; padding: 15px; margin-top: 20px; background-color: #f9f9f9;">
  <strong>BibTeX Citation:</strong>
  <pre style="font-family: monospace; white-space: pre-wrap; background: #f4f4f4; padding: 10px; border-radius: 5px; font-size: 0.7em;">
    @inproceedings{black2024multi,
    title={Multi-view Classification Using Hybrid Fusion and Mutual Distillation},
    author={Black, Samuel and Souvenir, Richard},
    booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
    pages={270--280},
    year={2024}
    }
  </pre>
</div>