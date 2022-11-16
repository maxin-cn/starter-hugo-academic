---
title: "Inconsistency-aware wavelet dual-branch network for face forgery detection"
authors:
- Gengyun Jia
- Meisong Zheng
- Chuanrui Hu
- Xin Ma
- Yuting Xu 
- Luoqi Liu
- Yafeng Deng
- Ran He

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""
publication: "*IEEE Transactions on Biometrics, Behavior, and Identity Science*"
publication_short: ""

abstract: Current face forgery techniques can generate high-ﬁdelity fake faces with extremely low labor and time costs. As a result, face forgery detection becomes an important research topic to prevent technology abuse. In this paper, we present an inconsistency-aware wavelet dual-branch network for face forgery detection. This model is mainly based on two kinds of forgery clues called inter-image and intra-image inconsistencies. To fully utilize them, we ﬁrstly enhance the forgery features by using additional inputs based on stationary wavelet decomposition (SWD). Then, considering the different properties of the two inconsistencies, we design a dual-branch network that predicts image-level and pixel-level forgery labels respectively. The segmentation branch aims to recognize real and fake local regions, which is crucial for discovering intra-image inconsistency. The classiﬁcation branch learns to discriminate the real and fake images globally, thus can extract inter-image inconsistency. Finally, bilinear pooling is employed to fuse the features from the two branches. We ﬁnd that the bilinear pooling is a kind of spatial attentive pooling. It effectively utilizes the rich spatial features learned by the segmentation branch. Experimental results show that the proposed method surpasses the state-of-the-art face forgery detection methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
summary: Published in IEEE Transactions on Biometrics, Behavior, and Identity Science, 2021

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9447758
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
