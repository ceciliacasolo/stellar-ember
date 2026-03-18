---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Get in touch
        url: mailto:casolocecilia@gmail.com
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Research and Applied Work'
      subtitle: ''
      text: |-
        I work on machine learning methods that stay meaningful when systems evolve over time.

        My work sits at the intersection of causality, dynamical systems, stochastic processes, and representation learning, with applications in biology and healthcare.

        I am interested in roles where rigorous ML research connects to real modeling problems, especially in trustworthy AI, foundation models, and scientific machine learning.
    design:
      columns: '1'
  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: resume-skills
    content:
      title: Research Areas
      username: me
  - block: resume-languages
    content:
      title: Languages
      username: me
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: All Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: 'Open to Conversation'
      text: |-
        If you are hiring, collaborating, or working on related machine learning problems, feel free to reach out by email or connect on LinkedIn.
      button:
        text: Email Me
        url: mailto:casolocecilia@gmail.com
    design:
      columns: '1'
---
