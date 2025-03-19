---
title: 'Derm: SLA-aware Resource Management for Highly Dynamic Microservices'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zizhao Mo
  - Huanle Xu
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - 'Corresponding Author'
  - ''


date: '2024-04-27'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-27'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS) 2024*
publication_short: In *ASPLOS 2024*

abstract: "Modern GPU clusters inherently exhibit heterogeneity, encompassing various aspects such as computation and communication. This heterogeneity poses a significant challenge for the elastic scheduling of deep learning workloads. Unfortunately, existing elastic schedulers often overlook the impact of heterogeneity on scaling efficiency, resulting in considerably prolonged job completion times.
In this paper, we present Heet, a new Heterogeneity-aware system explicitly developed for elastic training in DL clusters. Heet addresses two critical issues. First, it utilizes a 3-D collaborative filtering method to accurately measure the scaling efficiency of all elastic configurations on heterogeneous hosts, substantially reducing profiling overhead. Second, Heet introduces a unique price function to effectively balance scaling efficiency and scheduling efficiency. Building upon this function, Heet incorporates a scalable mechanism that employs minimum-weight full bipartite matching and opportunistic resource trading to generate dynamic scheduling decisions. Evaluations conducted on cloud clusters and large-scale simulations demonstrate that Heet can reduce job completion time by up to 2.46× compared to existing solutions.
"
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3620665.3640375'
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


