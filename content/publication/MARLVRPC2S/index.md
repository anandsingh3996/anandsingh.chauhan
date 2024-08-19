---
title: 'Multi-Agent Learning of Efficient Fulfilment and Routing Strategies in E-Commerce'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

  - Omkar Shelke
  - Pranavi Pathakota
  - admin
  - Hardik Meisheri
  - Harshad Khadilkar
  - Balaraman Ravindran
  - Dr. Mayank Baranwal
  - Ansuma Basumatary

author_notes:
- 'Equal contribution'
- 'Equal contribution'
- 'Equal contribution'

date: 'December 09, 2023'
doi: 'https://doi.org/10.48550/arXiv.2311.16171'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['workshop-paper']

# Publication name and optional abbreviated publication name.
publication: In *Generalisation in Planning (GenPlan) workshop, NeurIPS 2023*
publication_short: 'GenPlan Workshop, NeurIPS 2023'
abstract: 'This paper presents an integrated algorithmic framework for minimising product delivery costs in e-commerce (known as the cost-to-serve or C2S). One of the major challenges in e-commerce is the large volume of spatio-temporally diverse orders from multiple customers, each of which has to be fulfilled from one of several warehouses using a fleet of vehicles. This results in two levels of decision-making: (i) selection of a fulfillment node for each order (including the option of deferral to a future time), and then (ii) routing of vehicles (each of which can carry multiple orders originating from the same warehouse). We propose an approach that combines graph neural networks and reinforcement learning to train the node selection and vehicle routing agents. We include real-world constraints such as warehouse inventory capacity, vehicle characteristics such as travel times, service times, carrying capacity, and customer constraints including time windows for delivery. The complexity of this problem arises from the fact that outcomes (rewards) are driven both by the fulfillment node mapping as well as the routing algorithms, and are spatio-temporally distributed. Our experiments show that this algorithmic pipeline outperforms pure heuristic policies.'

tags:
  - Multi Agent Reinforcement Learning
  - Graph Neural Network
  - Supply Chain Network

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2311.16171'
url_poster: ''
url_project: ''
url_slides: ''

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
