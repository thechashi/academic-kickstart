---
title: 'DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities'

# Authors
authors:
  - Chashi Mahiul Islam
  - Xiuwen Liu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2025-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-01T00:00:00Z'

# Publication type.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: ArXiv Preprint
publication_short: ArXiv

abstract: |
  Multimodal Large Language Models (MLLMs) are at the forefront of AI technology, with DeepSeek models emerging as a leading open-source alternative. This paper implements an adapted embedding manipulation attack on DeepSeek Janus that induces targeted visual hallucinations through systematic optimization of image embeddings. Through extensive experimentation across COCO, DALL·E 3, and SVIT datasets, the research achieves hallucination rates of up to 98.0% while maintaining high visual fidelity (SSIM > 0.88). The analysis demonstrates that both 1B and 7B variants of DeepSeek Janus are susceptible. A novel multi-prompt hallucination detection framework using LLaMA-3.1 8B Instruct is introduced for robust evaluation.

# Summary. An optional shortened abstract.
summary: |
  This study induces targeted visual hallucinations in DeepSeek Janus models through embedding manipulation, achieving up to 98% success rates while maintaining image fidelity.

tags:
  - MLLMs
  - DeepSeek
  - Hallucinations
  - Adversarial Attacks
  - AI Security

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2502.14811'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
projects:
  - mllm_hallucinations
---
