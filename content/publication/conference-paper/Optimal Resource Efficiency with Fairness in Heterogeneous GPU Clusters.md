---
title: 'Optimal Resource Efficiency with Fairness in Heterogeneous GPU Clusters'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zizhao Mo
  - Huanle Xu
  - Wing Cheong Lau


# Author notes (optional)
author_notes:
  - ''
  - 'Corresponding Author'
  - ''

date: '2024-12-02'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-02'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM/IFIP International Middleware Conference (Middleware) 2024*
publication_short: In *Middleware 2024*

abstract: "Ensuring the highest training throughput to maximize resource efficiency, while maintaining fairness among users, is critical for deep learning (DL) training in heterogeneous GPU clusters. However, current DL schedulers provide only limited fairness properties and suboptimal training throughput, impeding tenants from effectively leveraging heterogeneous resources. The underlying design challenge stems from inherent conflicts between efficiency and fairness properties.
In this paper, we introduce OEF, a new resource allocation framework specifically developed for achieving optimal resource efficiency and ensuring diverse fairness properties in heterogeneous GPU clusters. By integrating resource efficiency and fairness within a global optimization framework, OEF is capable of providing users with maximized overall efficiency, as well as various guarantees of fairness, in both cooperative and non-cooperative environments. We have implemented OEF in a cluster resource manager and conducted large-scale experiments, showing that OEF can improve the overall training throughput by up to 32% while improving fairness compared to state-of-the-art heterogeneity-aware schedulers."

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3652892.3654792'
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


