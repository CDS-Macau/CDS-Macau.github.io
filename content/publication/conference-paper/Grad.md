---
title: 'Grad: Intelligent Microservice Scaling by Harnessing Resource Fungibility'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Liao Chen
  - Chenyu Lin
  - Shutian Luo
  - Huanle Xu
  - Chengzhong Xu

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - 'Corresponding Author'

date: '2025-03-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The International Symposium on High-Performance Computer Architecture (HPCA) 2025*
publication_short: In *HPCA 2025*

abstract: This paper introduces Grad, an intelligent microservice scaling framework by harnessing resource fungibility between critical and non-critical microservices. Addressing the challenges posed by the dynamic nature of resource fungibility during scaling, Grad incorporates three key components.  First, Grad employs a modular learning approach to profile individual microservice latency in relation to environmental conditions. Utilizing gradient extracts from this profile, Grad designs a scalable optimization module to dynamically select the optimal set of microservices for scaling. To rapidly mitigate SLA violations, Grad also deploys an accurate end-to-end latency predictor, serving as an simulator to obtain real-time feedback. We evaluate Grad in our cluster using real microservice benchmarks and production traces, demonstrating its ability to reduce resource usage by 49.1\% and lower the probability of SLA violations by 3.7$\times$ when compared to state-of-the-art solutions. 
# Summary. An optional shortened abstract.
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


