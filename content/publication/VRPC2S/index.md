---
title: 'A Learning Approach for Discovering Cost-Efficient Integrated Sourcing and Routing Strategies in E-Commerce'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Omkar Shelke
  - Pranavi Pathakota
  - admin
  - Hardik Meisheri
  - Dr. Harshad Khadilkar
  - Dr. Balaraman Ravindran


date: 'Jan 04–07, 2024'
doi: '10.1145/3632410'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-04'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 7th Joint International Conference on Data Science & Management of Data (11th ACM IKDD CODS and 29th COMAD)*
publication_short: In *CODS-COMAD 2024*.

abstract: This paper presents an integrated algorithmic framework for minimising product delivery costs in e-commerce (known as the cost-to-serve or CTS). One of the major challenges plaguing is the large volume of dynamically generated orders from multiple customers, each of which has to be fulfilled from one of several warehouses using a fleet of vehicles. This results in two levels of decision-making: selection of a fulfillment node for each order (including the option of deferral to a future time), followed by routing of vehicles (each of which can carry multiple orders originating from the same warehouse). To handle this, we propose an approach that combines graph neural networks, reinforcement learning, and an existing vehicle routing heuristic. We include real-world constraints such as warehouse inventory capacity, vehicle characteristics such as travel times, service times, carrying capacity, and customer constraints including time windows for delivery. The complexity of this problem arises from the fact that outcomes (rewards) are driven both by the fulfillment node mapping as well as the routing algorithms, and are spatio-temporally distributed. The problem is formulated as a Markov Decision Process (MDP) and solved by using a Graph Auto Encoder (GAE) in combination with Deep Q-Learning for fulfillment node mapping. Our experiments show that this algorithmic pipeline outperforms pure heuristic policies.

tags:
  - Grpah Neural Network
  - Reinforcement Learning
  - Supply Chain

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
