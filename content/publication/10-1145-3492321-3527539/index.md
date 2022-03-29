---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Jiffy: Elastic Far-Memory for Stateful Serverless Analytics'
subtitle: ''
summary: ''
authors:
- Anurag Khandelwal
- admin
- Rachit Agarwal
- Aditya Akella
- Ion Stoica
tags:
- '"serverless computing"'
- '"data analytics"'
- '"far-memory"'
- '"function-as-a-service"'
categories: []
date: '2022-01-01'
lastmod: 2022-03-29T10:08:14-04:00
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
publishDate: '2022-03-29T14:08:07.513792Z'
publication_types:
- '1'
abstract: Stateful serverless analytics can be enabled using a remote memory system
  for inter-task communication, and for storing and exchanging intermediate data.
  However, existing systems allocate memory resources at job granularity---jobs specify
  their memory demands at the time of the submission; and, the system allocates memory
  equal to the job's demand for the entirety of its lifetime. This leads to resource
  underutilization and/or performance degradation when intermediate data sizes vary
  during job execution.This paper presents Jiffy, an elastic far-memory system for
  stateful serverless analytics that meets the instantaneous memory demand of a job
  at seconds timescales. Jiffy efficiently multiplexes memory capacity across concurrently
  running jobs, reducing the overheads of reads and writes to slower persistent storage,
  resulting in 1.6 -- 2.5× improvements in job execution time over production workloads.
  Jiffy implementation currently runs on Amazon EC2, enables a wide variety of distributed
  programming models including MapReduce, Dryad, StreamScope, and Piccolo, and natively
  supports a large class of analytics applications on AWS Lambda.
publication: '*Proceedings of the Seventeenth European Conference on Computer Systems(EuroSys)*'
url_pdf: https://doi.org/10.1145/3492321.3527539
url_code: https://github.com/resource-disaggregation/jiffy
doi: 10.1145/3492321.3527539
---
