---
title: 'Serving Hybrid LLM Loads with SLO Guarantees Using CPU-GPU Attention Piggybacking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zizhao Mo
  - Junlin Chen
  - Huanle Xu
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - 'Corresponding Author'
  - ''

date: '2026-02-23'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-23'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGMOD International Conference on Management of Data 2026*
publication_short: In *SIGMOD 2026*

abstract: "In this paper, we propose OmniServe, a novel LLM serving system that efficiently harnesses both CPU and GPU resources to mitigate interference and improve throughput. Central to OmniServe is the Attention Piggybacking mechanism, which effectively offloads the Attention computation of BE services to CPUs on the fly. This mechanism also facilitates asynchronous communication between CPU and GPU streams, preventing GPUs from being blocked while aggregating Attention results. Additionally, OmniServe incorporates a dynamic batching control policy to adapt to fluctuating request arrivals, facilitating Dense module computation using layer-wise batching. Experimental results show that OmniServe improves the SLO attainment rate for LS services by up to 1.48x while enhancing BE serving throughput by up to 9.85x compared to existing state-of-the-art systems."
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


