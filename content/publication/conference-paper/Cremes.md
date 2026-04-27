---
title: 'Cremes: Cost-Efficient and Reliable Microservice Execution on Spot Instances'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Liao Chen
  - Chenyu Lin
  - Junlin Chen
  - Shutian Luo
  - Huanle Xu
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding Author'
  - ''

date: '2026-04-27'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-27'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 35th International Symposium on High-Performance Parallel and Distributed Computing*
publication_short: In *HPDC 2026*

abstract: "While spot instances offer a cost-effective alternative to on-demand cloud resources, they introduce reliability challenges for latency-sensitive microservices due to preemption risks and unpredictable provisioning delays. Conventional resource management systems, which often rely on assumptions of immediate instance availability, fail to account for these operational realities—resulting in increased risk of SLO violations when deployed in spot-based environments. In this paper, we propose Cremes, an adaptive and cost-efficient scaling framework that ensures microservice recovery within the spot instance grace period. Cremes explicitly models both instance waiting time and microservice startup latency, leverages cloud-exposed availability metrics, and applies lightweight machine learning for end-to-end latency prediction. By integrating these components into a multi-dimensional optimization engine, Cremes minimizes cost while satisfying recovery and performance constraints. Evaluations on AWS instances using DeathStarBench, TrainTicket, and Alibaba trace-driven experiments show that Cremes reduces infrastructure cost by up to 37.1% and maintains SLO violation rates under preemptible environments below 6.7%."
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

---


