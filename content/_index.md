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
  - block: markdown
    content:
      title: 'Selected Experience'
      text: |-
        <div class="experience-grid">
          <article class="experience-card">
            <p class="experience-card__meta">Jul 2025 to Nov 2025 · Berlin</p>
            <h3>Applied Scientist Intern</h3>
            <p class="experience-card__org">Amazon Web Services (AWS) OpenSearch</p>
            <p>Worked on post-training and reinforcement-learning setups for 7B to 12B language models, with a focus on explicit reasoning and agentic exploration.</p>
          </article>
          <article class="experience-card">
            <p class="experience-card__meta">Sep 2024 to Dec 2024 · Boston</p>
            <h3>Visiting Graduate Student</h3>
            <p class="experience-card__org">Broad Institute of MIT and Harvard</p>
            <p>Collaborated in Caroline Uhler's group on hybrid dynamical modeling for longitudinal microbiome data.</p>
          </article>
          <article class="experience-card">
            <p class="experience-card__meta">Feb 2022 to Present · Munich</p>
            <h3>PhD Candidate in Computer Science</h3>
            <p class="experience-card__org">Helmholtz Munich and Technical University of Munich</p>
            <p>Researching causal machine learning and dynamical systems with applications in biology and healthcare, in the group of Niki Kilbertus.</p>
          </article>
          <article class="experience-card">
            <p class="experience-card__meta">Jan 2021 to Nov 2021 · Zurich</p>
            <h3>MSc Thesis Researcher</h3>
            <p class="experience-card__org">ETH Zurich</p>
            <p>Worked on causal fairness in machine learning, bridging individual-level and population-level notions of fairness.</p>
          </article>
          <article class="experience-card">
            <p class="experience-card__meta">Aug 2020 to Dec 2020 · Eindhoven</p>
            <h3>Data Science Intern</h3>
            <p class="experience-card__org">Philips Research</p>
            <p>Developed deep learning models for behavioral time-series simulation in healthcare applications.</p>
          </article>
          <article class="experience-card">
            <p class="experience-card__meta">Dec 2019 to Feb 2022 · Delft-Rotterdam</p>
            <h3>Consulting Director and Global Leadership Team</h3>
            <p class="experience-card__org">180 Degrees Consulting</p>
            <p>Led AI-focused consulting projects and coordinated operations across more than 45 branches in the EMEA network.</p>
          </article>
        </div>

        [See full experience](/experience/)
    design:
      columns: '1'
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
