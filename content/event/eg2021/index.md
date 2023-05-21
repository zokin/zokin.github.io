---
title: Volumetric Video Tutorial

event: Eurographics 2021 Conference
event_url: https://conferences.eg.org/eg2021/program/tutorials/

location: Online
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Low-cost volumetric video with consumer grade sensors.
abstract: "While high-end setups currently support different facets of volumetric capture technology applications like content creation and live telepresence, there is a need to transition towards lower cost, portable setups for digitizing human performances, which are alsomore suitable for experimentation and accessible research. To encourage progress towards this, a low-cost Volumetric Capture system was developed and made openly available along with documentation covering both its software and hardware aspects."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-05-03T16:30:00Z"
# date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2021-05-03T16:30:00Z"

authors: [Nikolaos Zioulis]
tags: [Volumetric]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Volumetric Capture @ VCL3D'
  focal_point: Right

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://vcl3d.github.io/VolumetricCapture/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- Hyper360
---

In this tutorial, apart from presenting and documenting its operational details, we will offer insights for its various design choices, the challenges that  were encountered, and the lessons learned. These span both hardware and software topics like the selection of sensors, the balancing of processing power and  costs, the  design of the system, and even tripod mounts to ensure the portability of the setup. The presented [Volumetric Capture](https://vcl3d.github.io/VolumetricCapture/) system has been remotely and on-site deployed in various places around the globe as one of its central design goals apart from affordability was its portability and usability. The tutorial will also describe  how these two important components for the aforementioned aspects have been addressed, namely the spatial (i.e. [StructureNet](https://vcl3d.github.io/StructureNet/)) and temporal alignment of the sensors, in ways that are sensor-agnostic – allowing for hybrid-sensor deployments – and scalable, offering flexible capturing scenarios. However, as expected, these design choices come at a cost, and the limitations of this approach will also be presented and discussed. Finally, the tutorial will present the work that has been supported and enabled by this low-cost volumetric capture system, showcasing potential uses. More importantly, taking into account the ongoing data-driven revolution, such systems can be used for easily collecting volumetric datasets, with an example being [HUMAN4D](https://github.com/tofis/human4d_dataset).

{{< gdocs src="https://docs.google.com/presentation/d/e/2PACX-1vQ-honLv8yzxH3mUg0T7MgrG-VXgMuOewrxJDTPWDGrKPis2q6KNHGysdj2I9qejApmmLcm33yQ77C9/embed?start=true&loop=true&delayms=5000" >}}