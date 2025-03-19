---
title: "Cloud Configuration Optimization for Recurring Batch-Processing Applications"

# 【1 改作者】Authors
authors:
  - Yang Liu
  - Huanle Xu 
  - Wing Cheong Lau

# 【如果需要特别申明作者信息，不需要可以注释，- "" 可以跳过作者】
author_notes:
  - 'Corresponding Authors'
  - ''
  - ''
# - ""
# - ""
# - ""
# - ""
# - ""
# - "Corresponding authors"
# - "Corresponding authors"

# 【3 论文时间】
date: "2023-02-17"
doi: ""
# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-17"

# Publication type.

# publication_types: ['Template']
# 【4 注释上一行并解开下一行注释】
publication_types: ["article-journal"]

# 【5 更新会议信息】Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Parallel and Distributed Systems (TPDS) 34(5)"
publication_short: ""

# 【6 填Abstract】
abstract: "Recognizing the diversity of Big Data analytic jobs, cloud providers offer a wide range of VM instance types or even clusters to cater for different use cases. The choice of cloud configurations can have a significant impact on the response time and running cost of batch-processing applications, which may need to be re-run regularly with cloud-scale resources. However, identifying the best cloud configuration with a low search cost is quite challenging due to i) the large and high-dimensional configuration space, ii) the time-varying cloud service cost (e.g., AWS Spot instances), and iii) job response time variation even given the same configuration. To tackle these challenges, we design and implement Accordia, a system that enables Adaptive Cloud Configuration Optimization for Recurring Data-Intensive Applications. By leveraging recent algorithmic advances in Gaussian Process UCB techniques, Accordia can unearth the cost-optimal configuration with a deadline constraint (i.e., maximum tolerated running time) under the time-varying cloud service cost. More importantly, Accordia manages to achieve a theoretical performance guarantee, sub-linearly increasing dynamic regret of the job completion cost. Using extensive trace-driven simulations and empirical measurements of our Kubernetes-based implementation, we demonstrate that Accordia can identify a near-cost-optimal configuration (i.e., within 10% of the optimum) after fewer than 20 runs from over 7000 candidate choices, which translates to a 2X-speedup and up to 17.9% cost-savings, when comparing to the state-of-the-art approach, CherryPick."

# Summary. An optional shortened abstract.
summary: 

tags: []
featured: false

# 【7 链接】 links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/document/10048581'
url_code: 'https://github.com/cuhk-mobitec/Accordia'
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


