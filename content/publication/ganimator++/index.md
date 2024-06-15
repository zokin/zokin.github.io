---
title: "Towards Practical Single-shot Motion Synthesis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Konstantinos Roditakis
- Spyridon Thermos
- admin

date: "2024-06-03T00:00:00Z" # "2023-06-18T00:00:00Z"
doi: "10.48550/arXiv.2406.01136"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *AI for 3D Generation Workshop, Computer Vision and Pattern Recognition Workshop*
publication_short: In *CVPRW24*

abstract: Despite the recent advances in the so-called “cold start” generation from text prompts, their needs in data and computing resources, as well as the ambiguities around intellectual property and privacy concerns pose certain counterarguments for their utility. An interesting and relatively unexplored alternative has been the introduction of unconditional synthesis from a single sample, which has led to interesting generative applications. In this paper we focus on single-shot motion generation and more specifically on accelerating the training time of a Generative Adversarial Network (GAN). In particular, we tackle the challenge of GAN’s equilibrium collapse when using mini-batch training by carefully annealing the weights of the loss functions that prevent mode collapse. Additionally, we perform statistical analysis in the generator and discriminator models to identify correlations between training stages and enable transfer learning. Our improved GAN achieves competitive quality and diversity on the Mixamo benchmark when compared to the original GAN architecture and a single-shot diffusion model, while being up to ×6.8 faster in training time from the former and ×1.75 from the latter. Finally, we demonstrate the ability of our improved GAN to mix and compose motion with a single forward pass. Project page available at https://moverseai.github.io/single-shot. 

# Summary. An optional shortened abstract.
summary: Practical Single-sample Generative AI

tags: [Motion Synthesis, Single-Sample Generative AI]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project
  url: https://moverseai.github.io/single-shot/
# - icon:
#   icon_pack: fab
#   name: PDF
#   url: 
# - name: Supplementary
#   url: 
# - icon:
#   icon_pack: fab
#   name: Video
#   url: 

url_pdf: 'https://arxiv.org/pdf/2406.01136'
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: 'https://moverseai.github.io/bundle/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'GANimator++'
  focal_point: "Smart"
  preview_only: false # true # false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Motion Synthesis

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
