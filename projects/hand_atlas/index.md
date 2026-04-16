---
title: KRASL
header: images/background.jpg
footer: images/background.jpg
header-dark: True
footer-dark: True
redirect_from:
  - hand_atlas
---

<h1 style="text-align: center;">Developing an Hand Atlas from Cone-Beam CT Images of Healthy Hands</h1>

{% include section.html %}

## Research Images

<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/images/projects/hand_atlas/atlas.png" alt="3D Carpal Model" style="width: auto; height: auto; border-radius: 5px;">
  <img src="/images/projects/hand_atlas/atlas.png" alt="Kinematics Analysis" style="width: auto; height: auto; border-radius: 5px;">
</div>

---

## Methodology and Goals

<p style="text-align: justify;">
This project involves developing an atlas of a healthy hand from cone-beam computed tomography (CBCT) scans. To address this, a curriculum learning-based CycleGan framework was developed to super-resolve CBCT images to match high-resolution peripheral quantitative computed tomography (HR-pQCT) scans. This hand atlas was developed to support automated erosion detection and quantification for rheumatoid arthritis, serving as an anatomical prior in a deep learning pipeline (atlas-guided nnUNet).
</p>

---
