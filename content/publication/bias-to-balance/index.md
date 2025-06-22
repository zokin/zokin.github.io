---
title: "From bias to balance: Leverage representation learning for bias-free MoCap solving"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Georgios Albanis
- admin
- Spyridon Thermos
- Anargyros Chatzitofis
- Kostas Kolomvatsos  

date: "2025-02-01T00:00:00Z" # "2023-06-18T00:00:00Z"
doi: "10.1016/j.cviu.2024.104241"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In Computer Vision and Image Understanding
publication_short: In *CVIU*

abstract: Motion Capture (MoCap) is still dominated by optical MoCap as it remains the gold standard. However, the raw captured data even from such systems suffer from high-frequency noise and errors sourced from ghost or occluded markers. To that end, a post-processing step is often required to clean up the data, which is typically a tedious and time-consuming process. Some studies tried to address these issues in a data-driven manner, leveraging the availability of MoCap data. However, there is a high-level data redundancy in such data, as the motion cycle is usually comprised of similar poses (e.g. standing still). Such redundancies affect the performance of those methods, especially in the rarer poses. In this work, we address the issue of long-tailed data distribution by leveraging representation learning. We introduce a novel technique for imbalanced regression that does not require additional data or labels. Our approach uses a Mahalanobis distance-based method for automatically identifying rare samples and properly reweighting them during training, while at the same time, we employ high-order interpolation algorithms to effectively sample the latent space of a Variational Autoencoder (VAE) to generate new tail samples. We prove that the proposed approach can significantly improve the results, especially in the tail samples, while at the same time is a model-agnostic method and can be applied across various architectures.

# Summary. An optional shortened abstract.
summary: Leverage representation learning to effectively address bias in human datasets. Automatically weight rare poses using Mahalanobis distance. Sample the latent space for generating tail samples.

tags: [Motion Capture, AI, Human Pose and Shape Estimation, Representation Learning, Robust Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project
  url: https://moverseai.github.io/noise-tail/
# - icon:
#   icon_pack: fab
#   name: PDF
#   url: https://openaccess.thecvf.com/content/ICCV2023W/CV4Metaverse/papers/Albanis_Noise-in_Bias-out_Balanced_and_Real-Time_MoCap_Solving_ICCVW_2023_paper.pdf
# - name: Supplementary
#   url: https://openaccess.thecvf.com/content/ICCV2023W/CV4Metaverse/supplemental/Albanis_Noise-in_Bias-out_Balanced_ICCVW_2023_supplemental.zip
# - icon:
#   icon_pack: fab
#   name: Video
#   url: https://youtu.be/62ncJL4D0Cw


# url_pdf: 'https://openaccess.thecvf.com/content/ICCV2023W/CV4Metaverse/papers/Albanis_Noise-in_Bias-out_Balanced_and_Real-Time_MoCap_Solving_ICCVW_2023_paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: 'https://moverseai.github.io/noise-tail/'
url_slides: ''
url_source: ''
# url_video: 'https://youtu.be/62ncJL4D0Cw'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'From Bias to Balance'
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
