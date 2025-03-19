---
title: 'Interference-aware Multiplexing for Deep Learning in GPU Clusters: A Middleware Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenyan Chen
  - Zizhao Mo
  - Huanle Xu
  - Keying Ye
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - 'Corresponding Author'
  - ''
  - ''

date: '2023-11-11'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-11'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference for High Performance Computing, Networking, Storage, and Analysis (SC) 2023*
publication_short: In *SC 2023*

abstract: A common strategy for improving efficiency in training deep learning entails multiplexing tasks on a single GPU. To mitigate the interference caused by multiplexing, existing approaches primarily employ kernel-level solutions to regulate GPU kernel execution, or harness hardware-level techniques to explicitly restrict GPU streaming multiprocessors and memory. Nevertheless, none of them perform satisfactorily in optimizing the completion time of tasks. In this paper, we present IADeep, a middleware solution designed to significantly improve multiplexing efficiency. The core concept is the co-optimization of task assignments within a cluster and interference mitigation on each device. IADeep coordinates the configuration of all co-located tasks in a less fine-grained fashion, effectively reducing interference and enhancing task training performance. Across the entire cluster, IADeep intelligently selects applications suitable for multiplexing to further amplify the advantages of optimizing task configurations. Evaluations on a 20 RTX 3090-GPU cluster demonstrate that IADeep can significantly outperform state-of-the-art multiplexing solutions.
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3581784.3607060'
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


