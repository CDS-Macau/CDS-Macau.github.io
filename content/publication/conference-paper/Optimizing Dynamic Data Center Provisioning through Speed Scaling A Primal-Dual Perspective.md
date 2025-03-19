---
title: 'Optimizing Dynamic Data Center Provisioning through Speed Scaling A Primal-Dual Perspective'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaosong Chen
  - Huanle Xu
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - 'Corresponding Author'
  - ''

date: '2024-06-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-17'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Symposium on Parallelism in Algorithms and Architectures (2024) SPAA*
publication_short: In *SPAA 2024*

abstract: In this paper, we address a new and practical problem that involves speed scaling of multiple servers within a data center. Specifically, we consider a scenario where each server can handle multiple jobs simultaneously, and the energy consumed is a piece-wise convex function that depends on processing speed. In addition, turning on a server incurs a substantial energy cost. To tackle this problem, we develop a new online primal-dual fitting framework. By leveraging this framework, we have found that the straightforward LIF algorithm, which allocates new workloads to servers based on their minimal idle times, attains a bounded competitive ratio in comparison to the optimal offline solution. Building upon this finding, we have designed a novel algorithm called BDST. BDST dynamically updates server provisioning based on a long-term evaluation of the trade-off between the cost of maintaining high-speed for current servers and the cost of powering on additional servers. One critical aspect of BDST is its remarkable constant competitive ratio of less than three, regardless of the shape of the energy function.
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3626183.3659956'
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


