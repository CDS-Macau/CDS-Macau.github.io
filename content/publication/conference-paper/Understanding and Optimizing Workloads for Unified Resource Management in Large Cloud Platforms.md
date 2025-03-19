---
title: 'Understanding and Optimizing Workloads for Unified Resource Management in Large Cloud Platforms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chengzhi Lu
  - Huanle Xu
  - Keying Ye
  - Guoyao Xu
  - Liping Zhang
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
  - 'Corresponding Author'

date: '2023-05-08'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-08'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Systems (EuroSys) 2023*
publication_short: In *EuroSys 2023*

abstract: "To fully utilize computing resources, cloud providers such as Google and Alibaba choose to co-locate online services with batch processing applications in their data centers. By implementing unified resource management policies, different types of complex computing jobs request resources in a consistent way, which can help data centers achieve global optimal scheduling and provide computing power with higher quality. To understand this new scheduling paradigm, in this paper, we first present an in-depth study of Alibaba's unified scheduling workloads. Our study focuses on the characterization of resource utilization, the application running performance, and scheduling scalability. We observe that although computing resources are significantly over-committed under unified scheduling, the resource utilization in Alibaba data centers is still low. In addition, existing resource usage predictors tend to make severe overestimations. At the same time, tasks within the same application behave fairly consistently, and the running performance of tasks can be well-profiled with respect to resource contention on the corresponding physical host.
Based on these observations, in this paper, we design Optum, a unified data center scheduler for improving the overall resource utilization while ensuring good performance for each application. Optum formulates an optimization problem to schedule unified task requests, aiming to balance the trade-off between utilization and resource contention. Optum also implements efficient heuristics to solve the optimization problem in a scalable manner. Large-scale experiments demonstrate that Optum can save up to 15% of resources without performance degradation compared to state-of-the-art unified scheduling schemes."
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3552326.3587437'
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


