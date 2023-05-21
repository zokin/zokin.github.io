---
title: "Fast deformable model-based human performance capture and FVV using consumer-grade RGB-D sensors"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Dimitrios S. Alexiadis
- admin
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2018-02-13T00:00:00Z"
doi: "10.1016/j.patcog.2018.02.013"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Pattern Recognition, Elsevier*
publication_short: In *PR18*

abstract: In this paper, a novel end-to-end system for the fast reconstruction of human actor performances into 3D mesh sequences is proposed, using the input from a small set of consumer-grade RGB-Depth sensors. The proposed framework, by offline pre-reconstructing and employing a deformable actor’s 3D model to constrain the on-line reconstruction process, implicitly tracks the human motion. Handling non-rigid deformation of the 3D surface and applying appropriate texture mapping, it finally produces a dynamic sequence of temporally-coherent textured meshes, enabling realistic Free Viewpoint Video (FVV). Given the noisy input from a small set of low-cost sensors, the focus is on the fast (“quick-post”), robust and fully-automatic performance reconstruction. Apart from integrating existing ideas into a complete end-to-end system, which is itself a challenging task, several novel technical advances contribute to the speed, robustness and fidelity of the system, including a layered approach for model-based pose tracking, the definition and use of sophisticated energy functions, parallelizable on the GPU, as well as a new texture mapping scheme. The experimental results on a large number of challenging sequences, and comparisons with model-based and model-free approaches, demonstrate the efficiency of the proposed approach.

# Summary. An optional shortened abstract.
summary: Fast template-based performance capture.

tags: [Volumetric]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: http://vcl.iti.gr/performancecapture/
- icon:
  icon_pack: fab
  name: PDF
  url: https://www.iti.gr/iti/files/document/publications/RGB-D_09-03-2018.pdf
- icon:
  icon_pack: fab
  name: Data
  url: http://vcl.iti.gr/dataset/dataset-of-multiple-kinect2-rgb-d-streams/
- name: Supplementary
  url: https://ars.els-cdn.com/content/image/1-s2.0-S0031320318300657-mmc1.pdf
- icon:
  icon_pack: fab
  name: Video
  url: https://youtu.be/RHViHg75kh8

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
  caption: 'Performance Capture Results'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Hyper360

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the ***Cite*** button above to copy/download publication metadata (*.bib).
{{% /callout %}}

{{< gallery album="template-gallery" >}}

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->
