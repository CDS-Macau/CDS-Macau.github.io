---
title: "An In-Depth Study of Microservice Call Graph and Runtime Performance"

# 【1 改作者】Authors
authors:
  - Shutian Luo
  - Huanle Xu 
  - Chengzhi Lu
  - Kejiang Ye
  - Guoyao Xu
  - Liping Zhang 
  - Jian He 
  - Chengzhong Xu 

# 【如果需要特别申明作者信息，不需要可以注释，- "" 可以跳过作者】
author_notes:
  - 'Co-first Author'
  - 'Co-first Author'
  - ''
  - 'Corresponding Authors'
  - ''
  - ''
  - ''
  - 'Corresponding Authors'
# - ""
# - ""
# - ""
# - ""
# - ""
# - ""
# - "Corresponding authors"
# - "Corresponding authors"

# 【3 论文时间】
date: "2022-05-12"
doi: ""
# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-12"

# Publication type.

# publication_types: ['Template']
# 【4 注释上一行并解开下一行注释】
publication_types: ["article-journal"]

# 【5 更新会议信息】Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Parallel and Distributed Systems (TPDS), 33(12)"
publication_short: ""

# 【6 填Abstract】
abstract: "Loosely-coupled and light-weight microservices running in containers are replacing monolithic applications gradually. Understanding the characteristics of microservices is critical to make good use of microservice architectures. However, there is no comprehensive study about microservice and its related systems in production environments so far. In this paper, we present a solid analysis of large-scale deployments of microservices at Alibaba clusters. Our study focuses on the characterization of microservice dependency as well as its runtime performance. We conduct an in-depth anatomy of microservice call graphs to quantify the difference between them and traditional DAGs of data-parallel jobs. In particular, we observe that microservice call graphs are heavy-tail distributed and their topology is similar to a tree and moreover, many microservices are hot-spots. We also discover that the structure of call graphs for long-term developed applications is much simpler so as to provide better performance. Our investigation on microservice runtime performance indicates most microservices are much more sensitive to CPU interference than memory interference. Moreover, we design resource management policies to efficiently tune memory resources."

# Summary. An optional shortened abstract.
summary: 

tags: []
featured: false

# 【7 链接】 links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/document/9774016'
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
  caption: ''
  focal_point: ""
  preview_only: false

---


