---
title: 'Embracing Imbalance: Dynamic Load Shifting among Microservice Containers in Shared Clusters'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shutian Luo
  - Jianxiong Liao
  - Chenyu Lin
  - Huanle Xu
  - Zhi Zhou
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - 'Co-first Author'
  - 'Co-first Author'
  - ''
  - 'Corresponding Author'
  - 'Corresponding Author'

date: '2025-03-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS) 2025*
publication_short: In *ASPLOS 2025*

abstract: In this paper, we utilize an alternative approach by leveraging load imbalance. The central concept involves the dynamic load shifting across microservice containers with a focus on imbalance awareness. However, achieving seamless integration between load shifting and resource scaling, while accommodating the demands of partial connection between upstream and downstream containers, remains a challenge. To address this challenge, we introduce Imbres—a new microservice system that optimizes load shifting, connection management, and resource scaling in tandem. One significant advantage of Imbres lies in its rapid responsiveness, relying solely on online gradients of latency, eliminating the need for offline profiling. Evaluation using real microservice benchmarks reveals that Imbres reduces resource allocation by up to 62% and decreases SLA violation probability by up to 82%, compared to state-of-the-art systems.
# Summary. An optional shortened abstract.
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


