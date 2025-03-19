---
title: "Optimizing Resource Management for Shared Microservices: A Scalable System Design"

# 【1 改作者】Authors
authors:
  - Shutian Luo
  - Chenyu Lin 
  - Kejiang Ye
  - Guoyao Xu
  - Liping Zhang 
  - Guodong Yang 
  - Huanle Xu 
  - Chengzhong Xu 

# 【如果需要特别申明作者信息，不需要可以注释，- "" 可以跳过作者】
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding Authors'
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
date: "2024-02-13"
doi: ""
# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-13"

# Publication type.

# publication_types: ['Template']
# 【4 注释上一行并解开下一行注释】
publication_types: ["article-journal"]

# 【5 更新会议信息】Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Computer Systems (ToCS), 42(1-2)"
publication_short: ""

# 【6 填Abstract】
abstract: We present an efficient resource management system, namely Erms, for guaranteeing SLAs with high probability in shared microservice environments. Erms profiles microservice latency as a piece-wise linear function of the workload, resource usage, and interference. Based on this profiling, Erms builds resource scaling models to optimally determine latency targets for microservices with complex dependencies. Erms also designs new scheduling policies at shared microservices to further enhance resource efficiency. Experiments across microservice benchmarks as well as trace-driven simulations demonstrate that Erms can reduce SLA violation probability by 5× and more importantly, lead to a reduction in resource usage by 1.6×, compared to state-of-the-art approaches.

# Summary. An optional shortened abstract.
summary: 

tags: []
featured: false

# 【7 链接】 links:
# - name: ""
#   url: ""
url_pdf: 'https://dl.acm.org/doi/10.1145/3631607'
url_code: 'https://github.com/Cloud-and-Distributed-Systems/Erms'
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


