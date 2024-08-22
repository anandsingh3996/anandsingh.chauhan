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
        I am a researcher in the Data and Decision Sciences Group at Tata Consultancy Services Limited-Research, Mumbai. My work focuses on applying reinforcement learning (RL) and generative AI (GenAI) to solve real-world challenges.

        By combining qualitative and quantitative methods, I explore the intricate relationship between science, technology, and the economy.

        I am always open to collaboration opportunities. Feel free to reach out! 😃
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
      title: [July,2024]
      subtitle: ''
      text: 'Happy to be awarded the nasscom ai Gamechangers Award 2024 in AI research category for our work on reinforcement learning based control of power networks. '
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
