---
title: 'The Power of Prediction Microservice Auto Scaling via Workload Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shutian Luo
  - Huanle Xu
  - Kejiang Ye
  - Guoyao Xu
  - Liping Zhang
  - Guodong Yang
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - 'Co-first Author'
  - 'Co-first Author'
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding Author'

date: '2022-11-07'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-07'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Symposium on Cloud Computing (ACM SoCC) 2022*
publication_short: In *ACM SoCC 2022*

abstract: When deploying microservices in production clusters, it is critical to automatically scale containers to improve cluster utilization and ensure service level agreements (SLA). Although reactive scaling approaches work well for monolithic architectures, they are not necessarily suitable for microservice frameworks due to the long delay caused by complex microservice call chains. In contrast, existing proactive approaches leverage end-to-end performance prediction for scaling, but cannot effectively handle microservice multiplexing and dynamic microservice dependencies. In this paper, we present Madu, a proactive microservice auto-scaler that scales containers based on predictions for individual microservices. Madu learns workload uncertainty to handle the highly dynamic dependency between microservices. Additionally, Madu adopts OS-level metrics to optimize resource usage while maintaining good control over scaling overhead. Experiments on large-scale deployments of microservices in Alibaba clusters show that the overall prediction accuracy of Madu can reach as high as 92.3% on average, which is 13% higher than the state-of-the-art approaches. Furthermore, experiments running real-world microservice benchmarks in a local cluster of 20 servers show that Madu can reduce the overall resource usage by 1.7X compared to reactive solutions, while reducing end-to-end service latency by 50%.
# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3542929.3563477'
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


