---
title: 'Erms: Efficient Resource Management for Shared Microservices with SLA Guarantees'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shutian Luo
  - Huanle Xu
  - Kejiang Ye
  - Guoyao Xu
  - Liping Zhang
  - Jian He
  - Guodong Yang
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - 'Co-first Author'
  - 'Co-first Author'
  - ''
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding Author'

date: '2022-12-21'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-21'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS) 2023*
publication_short: In *ASPLOS 2023*

abstract: "A common approach to improving resource utilization in data centers is to adaptively provision resources based on the actual workload. One fundamental challenge of doing this in microservice management frameworks, however, is that different components of a service can exhibit significant differences in their impact on end-to-end performance. To make resource management more challenging, a single microservice can be shared by multiple online services that have diverse workload patterns and SLA requirements.
We present an efficient resource management system, namely Erms, for guaranteeing SLAs in shared microservice environments. Erms profiles microservice latency as a piece-wise linear function of the workload, resource usage, and interference. Based on this profiling, Erms builds resource scaling models to optimally determine latency targets for microservices with complex dependencies. Erms also designs new scheduling policies at shared microservices to further enhance resource efficiency. Experiments across microservice benchmarks as well as trace-driven simulations demonstrate that Erms can reduce SLA violation probability by 5× and more importantly, lead to a reduction in resource usage by 1.6×, compared to state-of-the-art approaches."
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3567955.3567964'
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


