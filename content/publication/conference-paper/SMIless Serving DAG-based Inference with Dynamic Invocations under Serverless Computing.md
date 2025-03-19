---
title: 'SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chengzhi Lu
  - Huanle Xu
  - Yudan Li
  - Wenyan Chen
  - Kejiang Ye
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - 'Corresponding Author'
  - ''
  - ''
  - ''
  - 'Corresponding Author'

date: '2024-11-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-17'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference for High Performance Computing, Networking, Storage, and Analysis (SC) 2024*
publication_short: In *SC 2024*

abstract: "The deployment of ML serving applications, featuring multiple inference functions on serverless platforms, has gained substantial popularity, leading to numerous developments of new systems. However, these systems often focus on optimizing resource provisioning and cold start management separately, ultimately resulting in higher monetary costs.
This paper introduces SMIless, a highly efficient serverless system tailored for serving DAG-based ML inference in heterogeneous environments. SMIless effectively co-optimizes resource configuration and cold-start management in the context of dynamic invocations. This is achieved by seamlessly integrating adaptive pre-warming windows, striking an effective balance between performance and cost. We have implemented SMIless on top of OpenFaaS and conducted extensive evaluations using real-world ML serving applications. The experimental results demonstrate that SMIless can achieve up to a 5.73 × reduction in the overall costs while meeting the SLA requirements for all user requests, surpassing the performance of state-of-the-art solutions."
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1109/SC41406.2024.00044'
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


