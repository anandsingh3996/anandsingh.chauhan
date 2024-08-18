---
title: "A Learning Approach for Discovering Cost-Efficient Integrated Sourcing and Routing Strategies in E-Commerce"
authors:
- Omkar Shelke
- Pranavi Pathakota
- admin
- Hardik Meisheri
- Harshad Khadilkar
- Balaraman Ravindran

author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2024-01-07"
doi: "10.1145/3632410"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-04"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 7th Joint International Conference on Data Science & Management of Data (11th ACM IKDD CODS and 29th COMAD)
"
publication_short: "CODS-COMAD 2024"

abstract: This paper presents an integrated algorithmic framework for minimising product delivery costs in e-commerce (known as the cost-to-serve or CTS). One of the major challenges plaguing is the large volume of dynamically generated orders from multiple customers, each of which has to be fulfilled from one of several warehouses using a fleet of vehicles. This results in two levels of decision-making: selection of a fulfillment node for each order (including the option of deferral to a future time), followed by routing of vehicles (each of which can carry multiple orders originating from the same warehouse). To handle this, we propose an approach that combines graph neural networks, reinforcement learning, and an existing vehicle routing heuristic. We include real-world constraints such as warehouse inventory capacity, vehicle characteristics such as travel times, service times, carrying capacity, and customer constraints including time windows for delivery. The complexity of this problem arises from the fact that outcomes (rewards) are driven both by the fulfillment node mapping as well as the routing algorithms, and are spatio-temporally distributed. The problem is formulated as a Markov Decision Process (MDP) and solved by using a Graph Auto Encoder (GAE) in combination with Deep Q-Learning for fulfillment node mapping. Our experiments show that this algorithmic pipeline outperforms pure heuristic policies.

tags:
- Graph Neural Network
- Reinforcement Learning
- Supply Chain Management
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/abs/10.1145/3632410.3632426
url_poster: ''
url_slides: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
