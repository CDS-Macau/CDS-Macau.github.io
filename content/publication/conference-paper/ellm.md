---
title: 'High Throughput and Low Latency LLM Serving via Adaptive KV Caching'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenyan Chen
  - Chengzhi Lu
  - Kejiang Ye
  - Huanle Xu
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - 'Corresponding Author'
  - ''

date: '2026-01-31'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-31'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of European Conference on Computer Systems (Eurosys) 2026*
publication_short: In *Eurosys 2026*

abstract: "The substantial memory demands of model weights and key-value (KV) caches often lead to severe memory bottlenecks in LLM serving. Existing systems address this by offloading KV caches to host memory and rapidly restoring them on demand before decoding. However, these approaches are too coarse-grained and fail to fully exploit the combined computational and storage capabilities of GPUs. In this paper, we introduce eLLM, a novel LLM serving system designed to achieve high throughput and low latency through fine-grained KV caching. The core innovation lies in adaptively storing partial tokens with KV caches while dynamically recomputing non-cached tokens in parallel with decoding, thereby balancing memory usage and computational efficiency. This new mechanism enables dual-level optimizations: At the request level, eLLM employs token-wise caching to adaptively adjust batch sizes and uncached token ratios in real time. At the layer level, eLLM leverages communication-computation overlap and kernel fusion for resource-complementary operations to further enhance throughput and reduce latency. Experiments demonstrate that eLLM achieves 3.03× higher throughput while satisfying strict per-output-token latency SLOs. It also reduces first-token latency by 2.63× compared to state-of-the-art systems. "
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


