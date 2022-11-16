---
title: "Contrastive attention network with dense field estimation for face completion"
authors:
- Xin Ma
- Xiaoqiang Zhou
- Huaibo Huang
- Gengyun Jia
- Zhenhua Chai 
- Xiaolin Wei
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-11-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Pattern Recognition*"
publication_short: ""

abstract: Most modern face completion approaches adopt an autoencoder or its variants to restore missing regions 
in face images. Encoders are often utilized to learn powerful representations that play an important role in meeting 
the challenges of sophisticated learning tasks. Speciﬁcally, various kinds of masks are often presented in face images 
in the wild, forming complex patterns, especially in this hard period of COVID- 19. It’s diﬃcult for encoders to 
capture such powerful representations under this complex situation. To  address this challenge, we propose a 
self-supervised Siamese inference network to improve the generalization and robustness of encoders. It can encode 
contextual semantics from full-resolution images and obtain more discriminative representations. To deal with geometric 
variations of face images, a dense correspondence ﬁeld is integrated into the network. We further propose a multi-scale 
decoder with a novel dual attention fusion module (DAF), which can combine the restored and known regions in an adaptive 
manner. This multi-scale architecture is beneﬁcial for the decoder to utilize discriminative representations learned from 
encoders into images. Extensive experiments clearly demonstrate that the proposed approach not only achieves more appealing 
results compared with state-of-the-art methods but also improves the performance of masked face recognition dramatically. 

# Summary. An optional shortened abstract.
summary: Image inpainting, 3D.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2112.10310
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
