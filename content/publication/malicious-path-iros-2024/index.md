---
title: "Malicious Path Manipulations via Exploitation of Representation Vulnerabilities of Vision-Language Navigation Systems"

# Authors
authors:
  - Chashi Mahiul Islam
  - Shaeke Salman
  - Montasir Shams
  - Xiuwen Liu
  - Piyush Kumar

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2024-07-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-08T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IROS 2024*
publication_short: In *IROS*

abstract: |
  Building on the unprecedented capabilities of large language models for command understanding and zero-shot recognition of multi-modal vision-language transformers, visual language navigation (VLN) has emerged as an effective way to address multiple fundamental challenges toward a natural language interface to robot navigation. However, such vision-language models are inherently vulnerable due to the lack of semantic meaning of the underlying embedding space. Using a recently developed gradient-based optimization procedure, we demonstrate that images can be modified imperceptibly to match the representation of totally different images and unrelated texts for a vision-language model. Building on this, we develop algorithms that can adversarially modify a minimal number of images so that the robot will follow a route of choice for commands that require a number of landmarks. We demonstrate that experimentally using a recently proposed VLN system; for a given navigation command, a robot can be made to follow drastically different routes. We also develop an efficient algorithm to detect such malicious modifications reliably based on the fact that the adversarially modified images have much higher sensitivity to added Gaussian noise than the original images.

# Summary. An optional shortened abstract.
summary: |
  This study explores the vulnerabilities of vision-language navigation systems and demonstrates methods to exploit these vulnerabilities to manipulate robot navigation paths. It also presents an algorithm to detect such manipulations.

tags:
  - Vision-Language Navigation
  - Adversarial Attacks
  - Robot Navigation
  - Deep Learning

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
