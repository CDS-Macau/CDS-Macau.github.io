---
title: 'Multiplexing Dynamic Deep Learning Workloads with SLO-awareness in GPU Clusters'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - WenYan Chen
  - Chengzhi Lu
  - Huanle Xu
  - Kejiang Ye
  - Chengzhong Xu

# Author notes (optional)
author_notes:
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
publication: In *The European Conference on Computer Systems*
publication_short: In *Eurosys 2025*

abstract: In this paper, we introduce Mudi, a new SLO-aware system designed to optimize the utilization of GPU resources within large-scale clusters. Mudi achieves this by efficiently multiplexing DL inference services with training tasks through spatial sharing. The fundamental concept behind Mudi involves profiling the latency of inference services using a piece-wise linear function that accurately captures resource interference. Leveraging this quantification of interference, Mudi designs a scalable cluster-wide co-location policy, determining the optimal multiplexing of training tasks and inference services to maximize resource efficiency. Furthermore, Mudi incorporates adaptive batching and resource scaling mechanisms to rapidly adapt to the dynamic workloads. Experimental results demonstrate that Mudi improves 42% of GPU resource utilization and achieves up to 2.27x higher training efficiency while satisfying inference SLOs, as compared to state-of-the-art multiplexing methods.
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
  caption: ''
  focal_point: ''
  preview_only: false

---


