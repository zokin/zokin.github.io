---
title: "KBody: Towards general, robust, and aligned monocular whole-body estimation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- James F. O'Brien  

date: "2023-04-25T00:00:00Z" # "2023-06-18T00:00:00Z"
# doi: "10.1109/3DV.2019.00081"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)*
publication_short: In *CVPRW23*

abstract: KBody is a method for fitting a low-dimensional body model to an image. It follows a predict-and-optimize approach, relying on data-driven model estimates for the constraints that will be used to solve for the body’s parameters. Acknowledging the importance of high quality correspondences, it leverages “virtual joints” to improve fitting performance, disentangles the optimization between the pose and shape parameters, and integrates asymmetric distance fields to strike a balance in terms of pose and shape capturing capacity, as well as pixel alignment. We also show that generative model inversion offers a strong appearance prior that can be used to complete partial human images and used as a building block for generalized and robust monocular body fitting.

# Summary. An optional shortened abstract.
summary: Shape-aware, pixel-aligned human body fitting to general monocular images.

tags: [Body, AI, Human Pose and Shape Estimation, Human-centric AI, Virtual Try-On, Body Fitting]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project
  url: https://zokin.github.io/KBody/
- icon:
  icon_pack: fab
  name: Short Paper
  url: https://openaccess.thecvf.com/content/CVPR2023W/CVFAD/papers/Zioulis_KBody_Balanced_Monocular_Whole-Body_Estimation_CVPRW_2023_paper.pdf
- name: Supplementary
  url: https://openaccess.thecvf.com/content/CVPR2023W/RHOBIN/supplemental/Zioulis_KBody_Towards_General_CVPRW_2023_supplemental.pdf
# - icon:
  # icon_pack: fab
  # name: Video
  # url: https://youtu.be/xa7Fl2mD4CA?t=9020 


url_pdf: 'https://arxiv.org/pdf/2304.11542.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: 'https://zokin.github.io/KBody/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=gC8HZa8bCLo&t=1s&ab_channel=NikosZioulis'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'KBody'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Human-centric AI

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
