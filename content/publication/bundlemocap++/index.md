---
title: "BundleMoCap++: Efficient, robust and smooth motion capture from sparse multiview videos"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Georgios Albanis
- admin
- Kostas Kolomvatsos  

date: "2024-10-01T00:00:00Z" # "2023-06-18T00:00:00Z"
doi: "https://doi.org/10.1016/j.cviu.2024.104190"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Computer Vision and Image Understanding
publication_short: In *CVIU24*

abstract: Producing smooth and accurate motions from sparse videos without requiring specialized equipment and markers is a long-standing problem in the research community. Most approaches typically involve complex processes such as temporal constraints, multiple stages combining data-driven regression and optimization techniques, and bundle solving over temporal windows. These increase the computational burden and introduce the challenge of hyperparameter tuning for the different objective terms. In contrast, BundleMoCap++ offers a simple yet effective approach to this problem. It solves the motion in a single stage, eliminating the need for temporal smoothness objectives while still delivering smooth motions without compromising accuracy. BundleMoCap++ outperforms the state-of-the-art without increasing complexity. Our approach is based on manifold interpolation between latent keyframes. By relying on a local manifold smoothness assumption and appropriate interpolation schemes, we efficiently solve a bundle of frames using two or more latent codes. Additionally, the method is implemented as a sliding window optimization and requires only the first frame to be properly initialized, reducing the overall computational burden. BundleMoCap++’s strength lies in achieving high-quality motion capture results with fewer computational resources. To do this efficiently, we propose a novel human pose prior that focuses on the geometric aspect of the latent space, modeling it as a hypersphere, allowing for the introduction of sophisticated interpolation techniques. We also propose an algorithm for optimizing the latent variables directly on the learned manifold, improving convergence and performance. Finally, we introduce high-order interpolation techniques adapted for the hypersphere, allowing us to increase the solving temporal window, enhancing performance and efficiency.

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


url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S1077314224002716'
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: 'https://moverseai.github.io/bundle/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'BundleMoCap++'
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

![model](model.jpg)

{{% callout note %}}
Click the ***Cite*** button above to copy/download publication metadata (*.bib).
{{% /callout %}}

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->
