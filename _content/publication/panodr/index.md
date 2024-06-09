---
title: "PanoDR: Spherical Panorama Diminished Reality for Indoor Scenes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Vasileios Gkitsas
- Vladimiros Sterzentsenko
- admin
- Georgios Albanis
- Dimitrios Zarpalas

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-06-25T00:00:00Z"
# doi: "10.1109/3DV.2019.00081"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)*
publication_short: In *CVPRW21*

abstract: The rising availability of commercial 360 cameras that democratize indoor scanning, has increased the interest for novel applications, such as interior space re-design. Diminished Reality (DR) fulfills the requirement of such applications, to remove existing objects in the scene, essentially translating this to a counterfactual inpainting task. While recent advances in data-driven inpainting have shown significant progress in generating realistic samples, they are not constrained to produce results with reality mapped structures. To preserve the ‘reality’ in indoor (re-)planning applications, the scene’s structure preservation is crucial. To ensure structure-aware counterfactual inpainting, we propose a model that initially predicts the structure of a indoor scene and then uses it to guide the reconstruction of an empty – background only – representation of the same scene. We train and compare against other state-of-the-art methods on a version of the Structured3D dataset modified for DR, showing superior results in both quantitative metrics and qualitative results, but more interestingly, our approach exhibits a much faster convergence rate. Code and models are available at https://github.com/VCL3D/PanoDR/.

# Summary. An optional shortened abstract.
summary: Structure-aware indoor spherical image inpainting.

tags: [360, AI]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://vcl3d.github.io/PanoDR/
- icon:
  icon_pack: fab
  name: PDF
  url: https://openaccess.thecvf.com/content/CVPR2021W/OmniCV/papers/Gkitsas_PanoDR_Spherical_Panorama_Diminished_Reality_for_Indoor_Scenes_CVPRW_2021_paper.pdf 
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/VCL3D/PanoDR
- icon:
  icon_pack: fab
  name: Video
  url: https://www.youtube.com/watch?v=xa7Fl2mD4CA&t=26274s 


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
  caption: 'PanoDR'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- ATLANTIS

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
