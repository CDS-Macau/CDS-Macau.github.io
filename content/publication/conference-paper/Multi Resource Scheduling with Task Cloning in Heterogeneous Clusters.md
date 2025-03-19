---
title: 'Multi Resource Scheduling with Task Cloning in Heterogeneous Clusters'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Huanle Xu
  - Yang Liu
  - Wing Cheong Lau

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''

date: '2022-01-13'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-13'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Parallel Processing (ICPP) 2022*
publication_short: In *ICPP 2022*

abstract: "To mitigate the straggler effect, today’s systems and computing frameworks have adopted redundancy to launch extra copies for stragglers. Two limitations of the existing straggler-mitigation techniques, however, are that resource demand of tasks is only considered in the context of slots and, moreover, redundancy is seldom coordinated with job scheduling. To tackle these issues, in this paper, we present DollyMP, a job scheduler that addresses multi-resource scheduling with task cloning in heterogeneous clusters. DollyMP carefully combines SRPT (Shortest Remaining Processing Time) and SVF (Smallest Volume First) via knapsack optimization to schedule tasks with multi-resource demands and, in the meanwhile, dynamically launches task clones to yield a small job completion time. DollyMP is built on a strong mathematical foundation to guarantee near-optimal performance. The deployment of our Hadoop YARN prototype on a 30-node cluster demonstrates that DollyMP can reduce job response time by 50% under different cluster loads."
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3545008.3545093'
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


