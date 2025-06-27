---
title: 'Hetis: Serving LLMs in Heterogeneous GPU Clusters with Fine-grained and Dynamic Parallelism'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zizhao Mo
  - Jianxiong Liao
  - Huanle Xu 
  - Zhi Zhou
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - 'Corresponding Author'
  - ''
  - ''

date: '2025-06-27'
doi: ' '

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-27'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC) 2025*
publication_short: In *SC 2025*

abstract: "The significant resource demands in LLM serving prompts production clusters to fully utilize heterogeneous hardware by partitioning LLM models across a mix of high-end and low-end GPUs. However, existing parallelization approaches often struggle to scale efficiently in heterogeneous environments due to their coarse-grained and static parallelization strategies. In this paper, we introduce Hetis, a new LLM system tailored for heterogeneous GPU clusters. Hetis addresses two critical challenges:(1) memory inefficiency caused by the mismatch between memory capacity and computational power in heterogeneous devices, and (2) computational inefficiency arising from performance gaps across different LLM modules. To tackle these issues, Hetis employs a fine-grained and dynamic parallelism design. Specifically, it selectively parallelizes compute-intensive operations to reduce latency and dynamically distributes Attention computations to low-end GPUs at a head granularity, leveraging the distinct characteristics of each module. Additionally, Hetis features an online load dispatching policy that continuously optimizes serving performance by carefully balancing network latency, computational load, and memory intensity.  Evaluation results demonstrate that Hetis can improve serving throughput by up to $2.25X$ and reduce latency by $1.49X$ compared to existing systems. "
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


