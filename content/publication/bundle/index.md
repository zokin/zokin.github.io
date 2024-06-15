---
title: "BundleMoCap: Efficient, Robust and Smooth Motion Capture from Sparse Multiview Videos"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Georgios Albanis
- admin
- Kostas Kolomvatsos  

date: "2023-11-30T00:00:00Z" # "2023-06-18T00:00:00Z"
doi: "10.1145/3626495.3626511"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 20th ACM SIGGRAPH European Conference on Visual Media Production*
publication_short: In *CVMP23*

abstract: Capturing smooth motions from videos using markerless techniques typically involves complex processes such as temporal constraints, multiple stages with data-driven regression and optimization, and bundle solving over temporal windows. These processes can be inefficient and require tuning multiple objectives across stages. In contrast, BundleMoCap introduces a novel and efficient approach to this problem. It solves the motion capture task in a single stage, eliminating the need for temporal smoothness objectives while still delivering smooth motions. BundleMoCap outperforms the state-of-the-art without increasing complexity. The key concept behind BundleMoCap is manifold interpolation between latent keyframes. By relying on a local manifold smoothness assumption, we can efficiently solve a bundle of frames using a single code. Additionally, the method can be implemented as a sliding window optimization and requires only the first frame to be properly initialized, reducing the overall computational burden. BundleMoCap’s strength lies in its ability to achieve high-quality motion capture results with simplicity and efficiency.

# Summary. An optional shortened abstract.
summary: Robust Manifold-based Bundle MoCap Solving.

tags: [Motion Capture, Body, AI, Human Pose and Shape Estimation, Representation Learning, Robust Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project
  url: https://moverseai.github.io/bundle/
# - icon:
#   icon_pack: fab
#   name: PDF
#   url: 
# - name: Supplementary
#   url: 
# - icon:
#   icon_pack: fab
#   name: Video
#   url: https://www.youtube.com/watch?v=X9QLlEbKKnQ


url_pdf: 'https://arxiv.org/pdf/2311.12679'
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: 'https://moverseai.github.io/bundle/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=X9QLlEbKKnQ'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'BundleMoCap'
  focal_point: "Smart"
  preview_only: false # true # false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Motion Capture

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

![model](model.png)

{{% callout note %}}
Click the ***Cite*** button above to copy/download publication metadata (*.bib).
{{% /callout %}}

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->
