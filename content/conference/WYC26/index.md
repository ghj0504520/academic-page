---
title: "Proactive Microservice Scaling with Storage Consistency in Geo-Distributed Cloud"
authors:
- Xin-Bao Wu
- Li-Hsing Yen
- admin
date: "2026-12-11T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *2026 IEEE Global Communications Conference*
publication_short: In *GLOBECOM 2026*

abstract: As user demand becomes spatially dispersed, horizontal service scaling across geo-distributed servers is essential to reduce latency and meet SLAs. Reactive approaches often fail under uncertain demand and non-negligible rollout delays. We present the first joint formulation of proactive microservice placement, storage replica allocation, and VM provisioning that simultaneously accounts for VM rollout delays, write-broadcast consistency overhead, and CPU interference. These aspects were not jointly addressed in prior work. The resulting problem couples binary placement variables with prioritized feasibility requirements, making standard SAC inapplicable. Hence, we develop Hybrid Policy Gradient (HPG), an SAC extension with a Bernoulli relaxation for binary variables and a staged constraint-aware reward. Experiments show HPG improves SLA satisfaction over Reactive GA by 51%-165%, at a cost increase of at most 60.2% across all evaluated settings.

# Summary. An optional shortened abstract.
summary: we develop Hybrid Policy Gradient (HPG), an SAC extension with a Bernoulli relaxation for binary variables and a staged constraint-aware reward. Experiments show HPG improves SLA satisfaction over Reactive GA by 51%-165%, at a cost increase of at most 60.2% across all evaluated settings.

tags:
- NFV
- Resource Management
- RL

featured: false

hugoblox:
  ids: 
    doi: ""

links:
- type: pdf
  url: WYCGLOBECOM26.pdf
# - type: preprint
#  provider: arxiv
#  id: 1512.04133v1
# - type: code
#  url: https://github.com/HugoBlox/hugo-blox-builder
- type: slides
  url: ""
# - type: dataset
#  url: "#"
# - type: poster
#  url: "#"
# - type: source
#  url: "#"
# - type: video
#  url: https://youtube.com
#- type: custom
#  label: Custom Link
#  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!--
This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
-->
