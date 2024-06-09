---
title: "360° Surface Regression with a Hyper-Sphere Loss"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Antonis Karakottas
- admin
- Stamatis Samaras
- Dimitrios Ataloglou
- Vasileios Gkitsas
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-09-16T00:00:00Z"
doi: "10.1109/3DV.2019.00037"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2019 International Conference on 3D Vision (3DV)*
publication_short: In *3DV19*

abstract: Omnidirectional vision is becoming increasingly relevant as more efficient 360° image acquisition is now possible. However, the lack of annotated 360° datasets has hindered the application of deep learning techniques on spherical content. This is further exaggerated on tasks where ground truth acquisition is difficult, such as monocular surface estimation. While recent research approaches on the 2D domain overcome this challenge by relying on generating normals from depth cues using RGB-D sensors, this is very difficult to apply on the spherical domain. In this work, we address the unavailability of sufficient 360° ground truth normal data, by leveraging existing 3D datasets and remodelling them via rendering. We present a dataset of 360° images of indoor spaces with their corresponding ground truth surface normal, and train a deep convolutional neural network (CNN) on the task of monocular 360° surface estimation. We achieve this by minimizing a novel angular loss function defined on the hyper-sphere using simple quaternion algebra. We put an effort to appropriately compare with other state of the art methods trained on planar datasets and finally, present the practical applicability of our trained model on a spherical image re-lighting task using completely unseen data by qualitatively showing the promising generalization ability of our dataset and model.

# Summary. An optional shortened abstract.
summary: A hyper-sphere loss function for normal estimation.

tags: [360, AI]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://vcl3d.github.io/HyperSphereSurfaceRegression/
- icon:
  icon_pack: fab
  name: PDF
  url: https://arxiv.org/pdf/1909.07043.pdf
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/VCL3D/HyperSphereSurfaceRegression
- icon:
  icon_pack: fab
  name: Data
  url: https://vcl3d.github.io/3D60/

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
  caption: 'Indoor Panorama Surface Estimation'
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
