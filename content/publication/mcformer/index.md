---
title: "MCFormer: A Transformer-Based Detector for Molecular Communication with Accelerated Particle-Based Solution"
authors:
- admin
- Chenyao Bai
- Aoji Zhu
- Yunlong Zhu
- Kezhi Wang
author_notes:
- 
- "Corresponding Author"
- 
- "Corresponding Author"
date: "2023-09-28T00:00:00Z"
doi: "10.1109/LCOMM.2023.3303091"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Communications Letters"
publication_short: ""

abstract: Molecular communication (MC) enables communication at the nanoscale where traditional electromagnetic waves are ineffective, and accurate signal detection is essential for practical implementation. However, due to the lack of accurate mathematical models, statistical-based signal detection methods are not applicable, and existing deep learning-based models exhibit relative simplicity in design. This paper integrates ideas from natural language processing into MC and proposes the MCFormer, a detector based on the classical Transformer model. Additionally, we propose an accelerated particle-based simulation algorithm using matrix operations for rapid generation of high-quality training data with a lower complexity than traditional methods. The experimental results demonstrate that the MCFormer achieves nearly optimal accuracy in a noise-free environment, surpassing the performance of the Deep Neural Network (DNN). Moreover, MCFormer can show optimal performance in environments with significant levels of unknown noise. All the codes can be found at https://github.com/Xiwen-Lu/MCFormer.

# Summary. An optional shortened abstract.
summary: 

tags:
- Molecular Communication
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: 'https://github.com/Xiwen-Lu/MCFormer'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/10210368'
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'The whole framework.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
