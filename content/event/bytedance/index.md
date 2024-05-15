---
title:  In-Network Memory Management for Disaggregated Data Centers

event: ByteDance Infrastructure Lab Talk Series
#event_url: 

location: In-person
address:

abstract: "Memory disaggregation promises transparent elasticity, high resource utilization and hardware heterogeneity in data centers by physically separating memory and compute into network-attached resource 'blades'. However, existing designs achieve performance at the cost of resource elasticity, restricting memory sharing to a single compute blade to avoid costly memory coherence traffic over the network.In this work, we show that emerging programmable network switches can enable an efficient shared memory abstraction for disaggregated architectures by placing memory management logic in the network fabric. We find that centralizing memory management in the network permits bandwidth and latency-efficient realization of in-network cache coherence protocols, while programmable switch ASICs support other memory management logic at line-rate. We realize these insights into MIND, an in-network memory management unit for rack-scale disaggregation. MIND enables transparent resource elasticity while matching the performance of prior memory disaggregation proposals for real-world workloads."
# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-07-19T13:00:00Z"
date_end: "2023-07-19T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2023-07-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

