---
title: "DronePose: Photorealistic UAV-Assistant Dataset Synthesis for 3D Pose Estimation via a Smooth Silhouette Loss"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Georgios Albanis
- admin
- Anastadios Dimou
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-01-03T00:00:00Z"
doi: "10.1007/978-3-030-66096-3_44"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 European Conference on Computer Vision Workshops (ECCVW)*
publication_short: In *ECCVW20*

abstract: In this work we consider UAVs as cooperative agents supporting human users in their operations. In this context, the 3D localisation of the UAV assistant is an important task that can facilitate the exchange of spatial information between the user and the UAV. To address this in a data-driven manner, we design a data synthesis pipeline to create a realistic multimodal dataset that includes both the exocentric user view, and the egocentric UAV view. We then exploit the joint availability of photorealistic and synthesized inputs to train a single-shot monocular pose estimation model. During training we leverage differentiable rendering to supplement a state-of-the-art direct regression objective with a novel smooth silhouette loss. Our results demonstrate its qualitative and quantitative performance gains over traditional silhouette objectives. Our data and code are available at https://vcl3d.github.io/DronePose.

# Summary. An optional shortened abstract.
summary: Gamification based data collection for drone 6DOF pose estimation.

tags: [Drone, AI]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://vcl3d.github.io/DronePose
- icon:
  icon_pack: fab
  name: PDF
  url: https://arxiv.org/pdf/2008.08823.pdf
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/VCL3D/DronePose
- icon:
  icon_pack: fab
  name: Data
  url: https://vcl3d.github.io/UAVA/
- name: Supplementary
  url: https://static-content.springer.com/esm/chp%3A10.1007%2F978-3-030-66096-3_44/MediaObjects/509073_1_En_44_MOESM1_ESM.zip
- icon:
  icon_pack: fab
  name: Video
  url: https://youtu.be/dSbeu238I-I

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
  caption: 'Photorealistic rendering for data synthesis.'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- FASTER

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

{{< gallery album="dronepose-gallery" >}}

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->
