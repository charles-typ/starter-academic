---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CHASE: Accelerating Distributed Pointer-Traversals on Disaggregated Memory'
subtitle: ''
summary: ''
authors:
- admin
- Seung-seob Lee
- Anurag Khandelwal
tags:
- '"Memory disaggregation"'
- '"Hardware Accelerator"'
categories: []
date: '2023-05-03'
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
publishDate: '2023-05-03T14:11:00.946896Z'
publication_types:
- '1'
abstract: Caches at CPU nodes in disaggregated memory architectures amortize the high data access latency over the network. However, such caches are fundamentally unable to improve performance for workloads requiring pointer traversals across linked data structures. We argue for accelerating these pointer traversals closer to disaggregated memory, in a manner that preserves expressiveness for supporting various linked structures, ensures energy efficiency and performance, and supports distributed execution. We design CHASE to meet all the above requirements for pointer-traversal workloads on rack-scale disaggregated memory through the principled use of FPGAbased SmartNICs and programmable network switches. Our evaluation of CHASE shows that it enables low-latency, highthroughput, and energy-efficient execution for a wide range of common pointer traversal workloads on disaggregated memory that fare poorly with caching alone.
publication: 'To appear (ASPLOS 2025)'
url_pdf: https://doi.org/10.48550/arXiv.2305.02388
#url_code: https://github.com/Yale-NeRD/mind
doi: 10.48550/arXiv.2305.02388
---
