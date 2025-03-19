---
title: 'PERT-GNN: Latency Prediction for Microservice-based Cloud-Native Applications via Graph Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Da Sun Handason Tam
  - Yang Liu
  - Huanle Xu
  - Siyue Xie
  - Wing Cheong Lau

# Author notes (optional)
author_notes:
  - ''
  - ''
  - 'Corresponding Author'
  - ''
  - ''

date: '2023-08-04'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-04'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD) 2023*
publication_short: In *KDD 2023*

abstract:  In this paper, we propose PERT-GNN, a generic graph neural network based framework to predict the end-to-end latency for microservice applications. PERT-GNN characterizes the interactions or dependency of component microservices observed from prior execution traces of the application using the Program Evaluation and Review Technique (PERT). We then construct a graph neural network based on the generated PERT Graphs, and formulate the latency prediction task as a supervised graph regression problem using the graph transformer method. PERT-GNN can capture the complex temporal causality of different microservice traces, thereby producing more accurate latency predictions for various applications. Evaluations based on datasets generated from common benchmarks and large-scale Alibaba microservice traces show that PERT-GNN can outperform other models by a large margin. In particular, PERT-GNN is able to predict the latency of microservice applications with less than 12% mean absolute percentage error.
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3580305.3599465'
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


