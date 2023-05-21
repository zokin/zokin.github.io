---
title: "OmniDepth: Dense Depth Estimation for Indoors Spherical Panoramas"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Antonis Karakottas
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2018-08-25T00:00:00Z"
doi: "10.1007/978-3-030-01231-1_28"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2018 European Conference on Computer Vision (ECCV)*
publication_short: In *ECCV18*

abstract: Recent work on depth estimation up to now has only focused on projective images ignoring   360∘  content which is now increasingly and more easily produced. We show that monocular depth estimation models trained on traditional images produce sub-optimal results on omnidirectional images, showcasing the need for training directly on   360∘  datasets, which however, are hard to acquire. In this work, we circumvent the challenges associated with acquiring high quality   360∘  datasets with ground truth depth annotations, by re-using recently released large scale 3D datasets and re-purposing them to   360∘  via rendering. This dataset, which is considerably larger than similar projective datasets, is publicly offered to the community to enable future research in this direction. We use this dataset to learn in an end-to-end fashion the task of depth estimation from   360∘  images. We show promising results in our synthesized data as well as in unseen realistic images.

# Summary. An optional shortened abstract.
summary: The first data-driven depth estimation method directly applied on 360∘ images.

tags: [360, AI]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: http://vcl.iti.gr/360-dataset/
- icon:
  icon_pack: fab
  name: PDF
  url: https://arxiv.org/pdf/1807.09620.pdf
- icon:
  icon_pack: fab
  name: Data
  url: http://vcl.iti.gr/360-dataset/
- name: Supplementary
  url: https://static-content.springer.com/esm/chp%3A10.1007%2F978-3-030-01231-1_28/MediaObjects/474211_1_En_28_MOESM1_ESM.pdf
  
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
  caption: 'A Spherical Panorama Depth Dataset'
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
