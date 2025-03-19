---
title: 'Characterizing Microservice Dependency and Performance: Alibaba Trace Analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shutian Luo
  - Huanle Xu
  - Chengzhi Lu
  - Kejiang Ye
  - Guoyaao Xu
  - Liping Zhang
  - Yu Ding
  - Jian He
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - 'Co-first Author'
  - 'Co-first Author'
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding Author'

date: '2021-11-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Symposium on Cloud Computing (ACM SoCC) 2021*
publication_short: In *ACM SoCC 2021*

abstract: "Loosely-coupled and light-weight microservices running in containers are replacing monolithic applications gradually. Understanding the characteristics of microservices is critical to make good use of microservice architectures. However, there is no comprehensive study about microservice and its related systems in production environments so far. In this paper, we present a solid analysis of large-scale deployments of microservices at Alibaba clusters. Our study focuses on the characterization of microservice dependency as well as its runtime performance. We conduct an in-depth anatomy of microservice call graphs to quantify the difference between them and traditional DAGs of data-parallel jobs. In particular, we observe that microservice call graphs are heavy-tail distributed and their topology is similar to a tree and moreover, many microservices are hot-spots. We reveal three types of meaningful call dependency that can be utilized to optimize microservice designs. Our investigation on microservice runtime performance indicates most microservices are much more sensitive to CPU interference than memory interference. To synthesize more representative microservice traces, we build a mathematical model to simulate call graphs. Experimental results demonstrate our model can well preserve those graph properties observed from Alibaba traces."
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3472883.3487003'
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


