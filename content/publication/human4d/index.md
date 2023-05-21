---
title: "HUMAN4D: A Human-Centric Multimodal Dataset for Motions and Immersive Media"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Anargyros Chatzitofis
- Leonidas Saroglou
- Prodromos Boutis
- Petros Drakoulis
- admin
- Shishir Subramanyam
- Bart Kevelham
- Caecilia Charbonnier
- Pablo Cesar
- Dimitrios Zarpalas
- Stefanos Kollias
- Petros Daras

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2020-09-23T00:00:00Z"
doi: "10.1109/ACCESS.2020.3026276"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *2020, IEEE Access*
publication_short: In *IEEEACCESS20*

abstract: We introduce HUMAN4D, a large and multimodal 4D dataset that contains a variety of human activities simultaneously captured by a professional marker-based MoCap, a volumetric capture and an audio recording system. By capturing 2 female and 2 male professional actors performing various full-body movements and expressions, HUMAN4D provides a diverse set of motions and poses encountered as part of single- and multi-person daily, physical and social activities (jumping, dancing, etc.), along with multi-RGBD (mRGBD), volumetric and audio data. Despite the existence of multi-view color datasets captured with the use of hardware (HW) synchronization, to the best of our knowledge, HUMAN4D is the first and only public resource that provides volumetric depth maps with high synchronization precision due to the use of intra- and inter-sensor HW-SYNC. Moreover, a spatio-temporally aligned scanned and rigged 3D character complements HUMAN4D to enable joint research on time-varying and high-quality dynamic meshes. We provide evaluation baselines by benchmarking HUMAN4D with state-of-the-art human pose estimation and 3D compression methods. We apply OpenPose and AlphaPose reaching 70.02% and 82.95% mAPPCKh-0.5 on single- and 68.48% and 73.94% mAPPCKh-0.5 on two-person 2D pose estimation, respectively. In 3D pose, a recent multi-view approach named Learnable Triangulation, achieves 80.26% mAPPCK3D-10cm. For 3D compression, we benchmark Draco, Corto and CWIPC open-source 3D codecs, respecting online encoding and steady bit-rates between 7-155 and 2-90 Mbps for mesh- and point-based volumetric video, respectively. Qualitative and quantitative visual comparison between mesh-based volumetric data reconstructed in different qualities and captured RGB, showcases the available options with respect to 4D representations. HUMAN4D is introduced to enable joint research on spatio-temporally aligned pose, volumetric, mRGBD and audio data cues. The dataset and its code are available online.

# Summary. An optional shortened abstract.
summary: Volumetric Data & MoCaP Dataset.

tags: [Volumetric]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://vcl.iti.gr/dataset/human4d/
- icon:
  icon_pack: fab
  name: PDF
  url: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9204617
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/tofis/human4d_dataset
- icon:
  icon_pack: fab
  name: Data
  url: https://ieee-dataport.org/open-access/human4d-human-centric-multimodal-dataset-motions-immersive-media

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
  caption: 'Volumetric Data & MoCaP Dataset'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- VRTogether

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
