---
title: "Noise-in, Bias-out: Balanced and Real-time MoCap Solving"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Georgios Albanis
- admin
- Spyridon Thermos
- Anargyros Chatzitofis
- Kostas Kolomvatsos  

date: "2023-10-03T00:00:00Z" # "2023-06-18T00:00:00Z"
# doi: "10.1109/3DV.2019.00081"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)*
publication_short: In *ICCVW23*

abstract: Real-time optical Motion Capture (MoCap) systems have not benefited from the advances in modern data-driven modeling.
In this work we apply machine learning to solve noisy unstructured marker estimates in real-time and deliver robust marker-based MoCap even when using sparse affordable sensors. To achieve this we focus on a number of challenges related to model training, namely the sourcing of training data and their long-tailed distribution. Leveraging representation learning we design a technique for imbalanced regression that requires no additional data or labels and improves the performance of our model in rare and challenging poses. By relying on a unified representation, we show that training such a model is not bound to high-end MoCap training data acquisition, and instead, can exploit the advances in marker-less MoCap to acquire the necessary data. Finally, we take a step towards richer and affordable MoCap by adapting a body model-based inverse kinematics solution to account for measurement and inference uncertainty, further improving performance and robustness.

# Summary. An optional shortened abstract.
summary: Balanced and noise robust MoCap solving.

tags: [Motion Capture, Body, AI, Human Pose and Shape Estimation, Representation Learning, Robust Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://moverseai.github.io/noise-tail/
- icon:
  icon_pack: fab
  name: PDF
  url: https://openaccess.thecvf.com/content/ICCV2023W/CV4Metaverse/papers/Albanis_Noise-in_Bias-out_Balanced_and_Real-Time_MoCap_Solving_ICCVW_2023_paper.pdf
- name: Supplementary
  url: https://openaccess.thecvf.com/content/ICCV2023W/CV4Metaverse/supplemental/Albanis_Noise-in_Bias-out_Balanced_ICCVW_2023_supplemental.zip
- icon:
  icon_pack: fab
  name: Video
  url: https://youtu.be/62ncJL4D0Cw


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
  caption: 'Noise-in, Bias-out'
  focal_point: "Smart"
  preview_only: false

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

{{% callout note %}}
Click the ***Cite*** button above to copy/download publication metadata (*.bib).
{{% /callout %}}

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). 
-->
