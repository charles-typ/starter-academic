---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'MIND: In-Network Memory Management for Disaggregated Data Centers'
subtitle: ''
summary: ''
authors:
- Seung-seob Lee
- Yanpeng Yu
- admin
- Anurag Khandelwal
- Lin Zhong
- Abhishek Bhattacharjee
tags:
- '"Memory disaggregation"'
- '"Programmable networks"'
categories: []
date: '2021-01-01'
lastmod: 2022-03-29T10:11:01-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-03-29T14:11:00.946896Z'
publication_types:
- '1'
abstract: Memory disaggregation promises transparent elasticity, high resource utilization
  and hardware heterogeneity in data centers by physically separating memory and compute
  into network-attached resource \"blades\". However, existing designs achieve performance
  at the cost of resource elasticity, restricting memory sharing to a single compute
  blade to avoid costly memory coherence traffic over the network.In this work, we
  show that emerging programmable network switches can enable an efficient shared
  memory abstraction for disaggregated architectures by placing memory management
  logic in the network fabric. We find that centralizing memory management in the
  network permits bandwidth and latency-efficient realization of in-network cache
  coherence protocols, while programmable switch ASICs support other memory management
  logic at line-rate. We realize these insights into MIND1, an in-network memory management
  unit for rack-scale disaggregation. MIND enables transparent resource elasticity
  while matching the performance of prior memory disaggregation proposals for real-world
  workloads.
publication: '*Proceedings of the ACM SIGOPS 28th Symposium on Operating Systems Principles(SOSP)*'
url_pdf: https://doi.org/10.1145/3477132.3483561
url_code: https://github.com/Yale-NeRD/mind
doi: 10.1145/3477132.3483561
---
