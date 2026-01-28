---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    id: overview
    content:
      slides:
      - title: CDS Lab
        content: Cloud and Distributed Systems Lab
        align: left
        background:
          image:
            filename: background.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '200px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  # Bridging theoretical advancements with practical applications, the lab’s research fosters cutting-edge frameworks and systems tailored to the evolving demands of modern distributed infrastructures.
  # About
  - block: markdown
    content:
      title: "About CDS Lab"
      subtitle: ''
      text: "
      **CDS Lab**(Cloud and Distributed Systems Lab) is from the Department of Computer and Information Science at University of Macau, led by Prof. [Chengzhong Xu](https://www.fst.um.edu.mo/personal/czxu/) and Prof. [Huanle Xu](https://www.fst.um.edu.mo/personal/huanlexu/). The lab specializes in designing and implementing innovative software solutions at the OS and middleware layers for large-scale cloud and distributed systems. By tackling critical challenges in scalability, efficiency, and reliability, CDS Lab strives to optimize application performance and maximize resource utilization in complex computing environments. 
      "
    design:
      columns: '2'
      spacing:
        padding: ['100px', '0', '100px', '0']
      css_class: 

  # Research Topic
  - block: markdown
    id: research
    content:
      title: "Research Topics"
      text: '
      <br>
      A non-exhaustive list of research topics studied in our group include:
      <br>
      <ul>
        <li>**Microservice characterization and resource management**</li>
          <ul>Investigate the microservice architecture in a large scale and implement optimized cloud native systems for higher resource efficiency.</ul>
        <li>**System Support for Deep Learning Systems**</li>
          <ul>Employ system and algorithm co-design in heterogeneous/homogeneous GPU clusters to support efficient distributed deep learning, including both training and inference.</ul>
        <li>**Unified scheduling systems for large-scale cloud platforms**</li>
          <ul>Design unified schedulers in large-scale data centers to balance the trade-off between application performance, resource utilisation, and scheduling scalability.</ul>
      </ul>
      '
    design:
      columns: '1'
      spacing:
        padding: ['100px', '0', '100px', '0']
      css_class: 

  # News
  - block: markdown
    id: news
    content:
      title: "News"
      text: '
      **Dec 2025 -** FedSUV got accepted by INFOCOM 2026. <br>
      **Sep 2025 -** FedDance got accepted by SoCC 2025. <br>
      **Aug 2025 -** Congratulations to Wenyan for successfully defending her PhD thesis!<br>
      **Jun 2025 -** Hetis got accepted by SC 2025. <br>
      **Jun 2025 -** Congratulations to Zizhao for successfully defending his PhD thesis! <br>
      **Mar 2025 -** FFT got Accepted by ICS 2025.  <br>
      **Jan 2025 -** Imbres got accepted by ASPLOS 2025. <br>
      **Dec 2024 -** FastPERT got accepted by AAAI 2025. <br>
      **Nov 2024 -** Grad got accepted by HPCA 2025. <br>
      **Oct 2024 -** One paper (on analysis of  bandit algorithm) got accepted by Journal of Artificial Intelligence Research (JAIR).  <br>
      **July 2024 -** Mudi got accepted by Eurosys 2025. <br>
      **Jun 2024 -** SMIless got accepted by SC 2024. <br>
      **Apr 2024 -** One paper (on algorithm design and analysis) got accepted by SPAA 2024.  <br>
      **Mar 2024 -** Derm got accepted by ISCA 2024. <br>
      **Mar 2024 -** OEF got accepted by Middleware 2024. <br>
      **Nov 2023 -** Heet  got accepted by ASPLOS 2024. <br>
      **Oct 2023 -** One paper got accepted by ACM ToCS.  <br>
      **Jun 2023 -** IADeep got accepted by SC 2023. <br>
      **May 2023 -** PERT-GNN got accepted by KDD 2023. <br>
      **Feb 2023 -** One paper got accepted by TPDS. <br>
      **Jan 2023 -** Optum got accepted by Eurosys 2023. <br>
      '
    design:
      columns: '1'
      spacing:
        padding: ['100px', '0', '100px', '0']
      css_class: 

  # Members
  - block: people
    id: members
    content:
      title: Members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Professor
          - Postdoc
          - PhD Student
          - Master Student
          - Research Assistant
          - Visiting Scholar
          - Alumni
      sort_by: Params.role
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: false

  # Publications
  # - block: collection
  #   id: publications
  #   content:
  #     title: Publications
  #     subtitle: "You can also search all the papers [here](./publication)."
  #     text: 
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 
  #   design:
  #     view:  card     
  #     columns: '1'
  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      count: 10
      filters:
        folders:
          - "publication"
        publication_type: 
    design:
      view: citation
      columns: '1'

  # Contact
  - block: contact
    id: contact
    content:
      title: Contact
      coordinates:
        latitude: '22.1325'
        longitude: '113.5437'
      directions: Room 1048 Faculty of Science and Technology University of Macau, E11 Avenida da Universidade Taipa, Macau, China
    design:
      columns: '1'
---
