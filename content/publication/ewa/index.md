---
title: "Improving Camera Pose Estimation via Temporal EWA Surfel Splatting"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Alexandros Papachristou
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2017-10-09T00:00:00Z"
doi: "10.1109/ISMAR.2017.17"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2017 IEEE International Symposium on Mixed and Augmented Reality (ISMAR)*
publication_short: In *ISMAR17*

abstract: Camera pose estimation is a fundamental problem of Augmented Reality and 3D reconstruction systems. Recently, despite the new better performing direct methods being developed, state-of-the-art methods are still estimating erroneous poses due to sensor noise, environmental conditions and challenging trajectories. Adding a back-end mapping process, SLAM systems achieve better performance and are more robust, but require higher computational resources, limiting their applicability. Therefore, lighter solutions to improve the accuracy of pose estimates are required. In this work we demonstrate the effectiveness of lighter data structures, namely surface elements, and exploit the temporality of sensor data streams to accumulate moving camera frames and improve tracking. This representation allows us to splat a photometric and geometric model simultaneously and use it to improve the performance of dense RGB-D camera pose estimation methods. Exploiting Elliptical Weighted Average splatting to produce high quality photometric results also allows us to detect erroneous poses through a novel visual quality analysis process. We show evidence of the EWA temporal model's effectiveness in publicly available datasets and argue that point-based representations are a good candidate for building lighter systems that should be further explored.

# Summary. An optional shortened abstract.
summary: Point-based splatting for dense SLAM frontend systems.

tags: [SLAM]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Website
#   url: https://vcl3d.github.io/VolumetricCapture/

links:
- icon:
  icon_pack: fab
  name: PDF
  url: https://www.iti.gr/iti/files/document/work/EWA_ISMAR2017.pdf

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
  caption: 'Temporal Splatting Aggregation Scheme'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Factory2Fit

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
