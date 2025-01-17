---
layout: archive
permalink: /projects/inpainting-augmentation/
author_profile: true
---

<div style="text-align: center; margin-top: 20px;">
  <h1 style="margin-bottom: 10px;">Evaluation of Inpainting and Augmentation for Censored Image Queries</h1>
</div>

<div style="text-align: center;">
  <div style="display: flex; justify-content: center; margin: 0;">
    <ul style="list-style: none; padding: 0; display: flex; gap: 15px; justify-content: center; margin: 0;">
      <li><h3 style="margin: 0;">Samuel Black</h3></li>
      <li><h3 style="margin: 0;">Somayeh Keshavarz</h3></li>
      <li><h3 style="margin: 0;">Richard Souvenir</h3></li>
    </ul>
  </div>
  <h4 style="margin-top: 10px;">Published at IJCV 2021 & WACV 2020</h4>
</div>

<div style="display: flex; justify-content: center; margin-top: 10px;">
  <ul style="list-style: none; padding: 0; display: flex; gap: 25px; justify-content: center;">
    <li><a href="https://link.springer.com/article/10.1007/s11263-020-01403-1" target="_blank">Journal Paper (IJCV 2021)</a></li>
    <li><a href="https://openaccess.thecvf.com/content_WACV_2020/papers/Black_Evaluation_of_Image_Inpainting_for_Classification_and_Retrieval_WACV_2020_paper.pdf" target="_blank">Conference Paper (WACV 2020)</a></li>
    <li><a href="https://github.com/sblack15/CensoredImageQueries" target="_blank">Code</a></li>
  </ul>
</div>

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 20px; margin-top: 20px;">
  <div>
    <img src="/research/images/inpainting.png" alt="IJCV teaser" width="500"/>
  </div>
  <div style="font-size: 18px; max-width: 600px; text-align: justify;">
    Images can be censored by masking the region(s) of interest with a solid color or pattern. When a censored image is used for classification or matching, the mask itself may impact the results. Recent work in image inpainting and data augmentation provide two different approaches for dealing with censored images. In this work, we perform an extensive evaluation of these methods to understand if the impact of censoring can be mitigated for image classification and retrieval. Results indicate that modern learning-based inpainting approaches outperform augmentation strategies and that metrics typically used to evaluate inpainting performance (e.g., reconstruction accuracy) do not necessarily correspond to improved classification or retrieval, especially in the case of person-shaped masked regions.
  </div>
</div>

<div style="border: 1px solid #ccc; padding: 15px; margin-top: 20px; background-color: #f9f9f9;">
  <strong>BibTeX Citation:</strong>
  <pre style="font-family: monospace; white-space: pre-wrap; background: #f4f4f4; padding: 10px; border-radius: 5px; font-size: 0.7em;">
    @article{black2021inpainting,
    title={Evaluation of Inpainting and Augmentation for Censored Image Queries},
    author={Black, Samuel and Keshavarz, Somayeh and Souvenir, Richard},
    journal={International Journal of Computer Vision},
    volume={129},
    number={4},
    pages={977--997},
    year={2021},
    publisher={Springer}
    }

    @inproceedings{black2020inpainting,
    title={Evaluation of Image Inpainting for Classification and Retrieval},
    author={Black, Samuel and Keshavarz, Somayeh and Souvenir, Richard},
    booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
    pages={1234--1245},
    year={2020}
    }
  </pre>
</div>