---
title:  NIMBLE Task Scheduling for Serverless Analytics

event: Yale CSL group meeting
event_url: https://csl.yale.edu/

location: Online
address:

abstract: "Serverless platforms facilitate transparent resource elasticity and fine-grained billing, making them an attractive choice for data analytics. We find that while server-centric analytics frameworks typically optimize for job completion time (JCT), resource utilization and isolation via inter-job scheduling policies, serverless analytics requires optimizing for JCT and cost of execution instead, introducing a new scheduling problem. We present Caerus, a task scheduler for serverless analytics frameworks that employs a fine-grained NIMBLE scheduling algorithm to solve this problem. NIMBLE efficiently pipelines task executions within a job, minimizing execution cost while being Pareto-optimal between cost and JCT for arbitrary analytics jobs. To this end, NIMBLE models a wide range of execution parameters --- pipelineable and non-piplineable data dependencies, data generation, consumption and processing rates, etc. --- to determine the ideal task launch times. Our evaluation results show that in practice, Caerus is able to achieve both optimal cost and JCT for queries across a wide range of analytics workloads."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-03-19T13:00:00Z"
date_end: "2021-03-19T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-03-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

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

