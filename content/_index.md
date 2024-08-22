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
        I am a Researcher in the Decision Sciences Research Area at TCS Research, driven by a deep passion for leveraging machine learning and operational research to tackle complex, real-world challenges. My expertise spans across diverse domains, with a strong focus on reinforcement learning and its practical applications. From optimizing power networks and supply chains to pioneering peer-to-peer energy trading and advancing electric vehicle technology, I aim to bridge the gap between theoretical research and impactful, real-world solutions. I hold an M.Tech. in Electrical Engineering from the Indian Institute of Technology, Gandhinagar, where I conducted award-winning research on Peer-to-Peer Energy Trading. My thesis, supervised by Prof. Naran Pindoriya, earned recognition through the Grid-India Power Systems Award, placing me among the top fifteen recipients. I’ve also presented at conferences, with one paper under review and a patent filed. At TCS Research, I collaborate with experts like Dr. Mayank Baranwal and Dr. Harshad Khadilkar to apply reinforcement learning to uncertain real-world problems, including power and supply-chain networks. My work also explores innovative approaches, such as using attention models for vehicle routing with time windows and integrating large language models with reinforcement learning for enhanced train scheduling.'
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
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
    id: news
    content:
      title: Nasscom AI Gamechanger Award in Research Category
      subtitle: ''
      text: '[07-2024] Happy to share that we have been awarded the NASSCOM AI Gamechangers Award 2024 in the AI Research category for our work on reinforcement learning-based control of power networks. It’s a great honor to be among the top ten research projects. '
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
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build Your Academic Website Like This
      text: |-
        This site is powered by Hugo Blox Builder—the FREE, open-source website builder based on Hugo, trusted by over 250,000 academics.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Build anything effortlessly with blocks—no coding required!
        
        From landing pages and academic resumés to conferences and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
