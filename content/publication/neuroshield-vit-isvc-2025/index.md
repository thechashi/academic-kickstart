---
title: 'NeuroShield-ViT: Mechanistic Understandings of Representation Vulnerabilities and Engineering Robust Vision Transformers'

# Authors
authors:
  - Chashi Mahiul Islam
  - Jacob Chacko
  - Shunsuke Nishino
  - Xiuwen Liu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2025-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *20th International Symposium on Visual Computing (ISVC 2025)*
publication_short: In *ISVC 2025*

abstract: |
  Vision Transformers (ViTs) have demonstrated remarkable success in various computer vision tasks. However, they remain vulnerable to adversarial attacks that exploit small, imperceptible perturbations in the input. In this work, we provide a mechanistic understanding of representation vulnerabilities in ViTs, revealing how minor changes in the input layer propagate and amplify through the transformer layers. Based on these insights, we propose NeuroShield-ViT, a framework designed to identify and neutralize vulnerable neurons, significantly enhancing the adversarial robustness of the model. Our results show that NeuroShield-ViT improves classification accuracy by 54.85% against PGD attacks and 71.6% against IGO attacks on the ImageNet1K dataset.

# Summary. An optional shortened abstract.
summary: |
  This work explores mechanistic vulnerabilities in Vision Transformers and introduces NeuroShield-ViT to neutralize them, significantly boosting adversarial robustness on ImageNet1K.

tags:
  - Vision Transformers
  - Adversarial Robustness
  - Mechanistic Interpretability
  - AI Security

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - vit_analysis

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
