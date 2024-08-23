---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-08-18
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Display a call-to-action button under the biography
      button:
        text: Download CV
        url: uploads/resume.pdf
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        <div style="text-align: justify">
        
        My research is centered on advancing machine learning techniques, particularly reinforcement learning (RL) and optimization, to tackle complex challenges across various domains. The crux of my work lies in developing intelligent solutions that bridge the gap between theoretical advancements and their practical applications in critical infrastructure.
        
        1. **Networked Systems**: I focus on creating robust control and optimization strategies for networked systems, such as power grids, vehicle networks, and railway systems. By enhancing efficiency and reliability, this work aims to bolster the resilience and performance of essential infrastructure.
        
        2. **Supply Chain Management**:: I apply machine learning to optimize supply chain operations, directly addressing logistical challenges that impact efficiency and cost-effectiveness. This work is particularly relevant in the context of global supply chain disruptions, where AI-driven solutions can offer significant improvements.
        
        3. **Attention Models for Vehicle Routing**: I investigate the use of attention models to solve vehicle routing problems with time windows. This research contributes to advancements in transportation logistics, aiming to improve the efficiency of routing systems in dynamic environments.
        
        4. **Integration of Large Language Models and Reinforcement Learning**: I explore novel methodologies that combine large language models (LLMs) with RL to enhance scheduling and optimization across various networked systems, including innovative applications in train scheduling. This interdisciplinary approach seeks to push the boundaries of AI's capabilities in real-world scenarios.
        
        My research has led to presentations at prestigious conferences, including main track papers at AAAI and ECAI, as well as workshops at NeurIPS. I continue to contribute to the field with ongoing paper submissions and patent applications. My focus remains on advancing reinforcement learning and optimization techniques, particularly in their application to networked systems, where I aim to develop intelligent and efficient solutions for real-world challenges in power, transportation, and related fields.
        
        </div>
            design:
      columns: '1'
    
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

    
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  
  - block: collection
    id: news
    content:
      title: Recent News and Talks
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Number of pages to display (0 = all pages)
      count: 5
      # Filter criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Number of pages to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
