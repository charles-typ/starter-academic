---
title:  Jiffy - Elastic Far-Memory for Stateful Serverless Analytics

event: Huawei Cloud Seminar
#event_url: https://csl.yale.edu/

location: Online
address:

abstract: "Stateful serverless analytics can be enabled using a remote memory system for inter-task communication, and for storing and exchanging intermediate data. However, existing systems allocate memory resources at job granularity—jobs specify their memory demands at the time of the submission; and, the system allocates memory equal to the job’s demand for the entirety of its lifetime. This leads to resource underutilization and/or performance degradation when intermediate data sizes vary during job execution.This paper presents Jiffy, an elastic far-memory system for stateful serverless analytics that meets the instantaneous memory demand of a job at seconds timescales. Jiffy efficiently multiplexes memory capacity across concurrently running jobs, reducing the overheads of reads and writes to slower persistent storage, resulting in 1.6 – 2.5× improvements in job execution time over production workloads. Jiffy implementation currently runs on Amazon EC2, enables a wide variety of distributed programming models including MapReduce, Dryad, StreamScope, and Piccolo, and natively supports a large class of analytics applications on AWS Lambda."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-05-11T09:30:00Z"
date_end: "2022-05-11T10:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-05-11T00:00:00Z"

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
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

