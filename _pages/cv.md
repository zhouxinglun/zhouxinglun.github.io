---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Contact
- Email: xinglun2023@163.com
- Location: Guangzhou, China
- GitHub: [zhouxinglun](https://github.com/zhouxinglun)

## Education
- **South China University of Technology (SCUT)**, Master of Electronic Information, 2024 - 2027 (Expected)  
  Research Focus: Multimodal Image Understanding, Few-shot Segmentation.
- **South China Normal University (SCNU)**, Bachelor of Electronic Information Engineering, 2020 - 2024

## Research Interests
- Few-shot Learning: Few-shot semantic segmentation and adapting large models for data-scarce scenarios.
- Multimodal Learning: Vision-language models and cross-modal alignment (for example, CLIP-based research).
- Remote Sensing: SAR image denoising and interpretation.

## Technical Skills
- Deep Learning: PyTorch, PyTorch Lightning, SAM/SAM 2, CLIP
- Tools: LaTeX (Overleaf), BibTeX, Git, Linux

## Publications
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
