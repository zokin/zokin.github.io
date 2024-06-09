---
title: "Zeroth-Order Optimizer Benchmarking for 3D PerformanceCapture"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Alexandros Doumanoglou
- Petros Drakoulis
- Kyriaki Christaki
- admin
- Vladimiros Sterzentsenko
- Antonis Karakottas
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
author_notes:
- ""
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2021-06-10T00:00:00Z"
doi: "10.1145/3449639.3459354"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-07-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2021 Genetic and Evolutionary Computation Conference (GECCO)*
publication_short: In *GECCO21*

abstract: In the field of 3D Human Performance Capture, a high-quality 3D scan of the performer is rigged and skinned to an animatable 3D template mesh that is subsequently fitted to the captured performance’s RGB-D data. Template fitting is accomplished via solving for the template’s pose parameters that better explain the performance data at each recorded frame. In this paper, we challenge open implementations of zeroth-order optimizers to solve the template fitting problem in a human performance capture dataset. The objective function that we employ approximates, the otherwise costly to evaluate, 3D RMS hausdorff distance between the animated template and the 3D mesh reconstructed from the depth data (target mesh) at an individual recorded frame. We distinguish and benchmark the optimizers, in three different real-world scenarios, two of which are based on the geometric proximity of the template to the target in individual frames, while in the third one we fit the template sequentially to all target frames of the recorded sequence. Conclusions of this work can serve as a reference for future optimizer implementations and our findings can serve as a baseline for future multi-objective optimization approaches. We make part of our benchmark and experiment setup publicly available (https://github.com/VCL3D/nevergrad, https://github.com/VCL3D/PerformanceCapture/releases/).

# Summary. An optional shortened abstract.
summary: An openly available zeroth-order performance capture benchmark integrated in the nevergrad platform.

tags: [Volumetric]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://vcl3d.github.io/nevergrad/
# - icon:
#   icon_pack: fab
#   name: PDF
#   url: 
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/vcl3d/nevergrad/tree/perfcap_benchmark

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
  caption: 'The energy function.'
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

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->
