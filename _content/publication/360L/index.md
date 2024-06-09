---
title: "Deep Lighting Environment Map Estimation from Spherical Panoramas"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Vasileios Gkitsas
- admin
- Federico Alvarez
- Dimitrios Zarpalas
- Petros Daras

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-06-14T00:00:00Z"
doi: "10.1109/CVPRW50498.2020.00328"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)*
publication_short: In *CVPRW20*

abstract: Estimating a scene's lighting is a very important task when compositing synthetic content within real environments, with applications in mixed reality and postproduction. In this work we present a data-driven model that estimates an HDR lighting environment map from a single LDR monocular spherical panorama. In addition to being a challenging and ill-posed problem, the lighting estimation task also suffers from a lack of facile illumination ground truth data, a fact that hinders the applicability of data-driven methods. We approach this problem differently, exploiting the availability of surface geometry to employ image-based relighting as a data generator and supervision mechanism. This relies on a global Lambertian assumption that helps us overcome issues related to pre-baked lighting. We relight our training data and complement the model's supervision with a photometric loss, enabled by a differentiable image-based relighting technique. Finally, since we predict spherical spectral coefficients, we show that by imposing a distribution prior on the predicted coefficients, we can greatly boost performance. Code and models available at vcl3d.github.io/DeepPanoramaLighting.

# Summary. An optional shortened abstract.
summary: Stereo-based supervision via raytracing for self-supervised spherical panorama depth.

tags: [360, AI]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://vcl3d.github.io/DeepPanoramaLighting
- name: PDF
  url: https://arxiv.org/pdf/2005.08000.pdf
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/VCL3D/DeepPanoramaLighting
- icon:
  icon_pack: fab
  name: Video
  url: https://youtu.be/M7c69qxVzXY

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
  caption: 'Object relighting within indoor scenes'
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
