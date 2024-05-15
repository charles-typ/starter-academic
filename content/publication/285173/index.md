---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SHEPHERD: Serving DNNs in the Wild'
subtitle: ''
summary: ''
authors:
- Hong Zhang
- admin
- Anurag Khandelwal
- Ion Stoica
tags:
- '"GPU Scheduling"'
categories: []
date: '2023-04-17'
lastmod: 2023-04-17T10:11:01-04:00
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
publishDate: '2023-04-17T14:11:00.946896Z'
publication_types:
- '1'
abstract: Model serving systems observe massive volumes of inference requests for many emerging interactive web services. These systems need to be scalable, guarantee high system goodput and maximize resource utilization across compute units. However, achieving all three goals simultaneously is challenging since inference requests have very tight latency constraints (10 – 500 ms), and production workloads can be extremely unpredictable at such small time granularities. We present SHEPHERD, a model serving system that achieves all three goals in the face of workload unpredictability. SHEPHERD uses a two-level design that decouples model serving into planning and serving modules. For planning, SHEPHERD exploits the insight that while individual request streams can be highly unpredictable, aggregating request streams into moderately-sized groups greatly improves predictability, permitting high resource utilization as well as scalability. For serving, SHEPHERD employs a novel online algorithm that provides guaranteed goodput under workload unpredictability by carefully leveraging preemptions and model-specific batching properties. Evaluation results over production workloads show that SHEPHERD achieves up to 18.1X higher goodput and 1.8X better utilization compared to prior state-of-the-art, while scaling to hundreds of workers.
publication: '*20th USENIX Symposium on Networked Systems Design and Implementation (NSDI 23)*'
url_pdf: https://www.usenix.org/system/files/nsdi23-zhang-hong.pdf
#url_code: https://github.com/Yale-NeRD/mind
#doi: 10.1145/3477132.3483561
---
