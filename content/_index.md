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
  - block: collection
    id: selected-publications
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
    id: talks
    content:
      title: Talks and Presentations
      text: ''
      filters:
        folders:
          - events
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: papers
    content:
      title: Papers
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: 'Personal Interests'
      text: |-
        <div style="background:#eef3fa;border-radius:1.75rem;padding:2.25rem 1.5rem;margin-top:0.75rem;">
          <div style="display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:2rem;align-items:start;text-align:center;">
            <div>
              <div style="color:#e79b92;">
                <svg viewBox="0 0 24 24" width="52" height="52" fill="currentColor" style="display:inline-block;" aria-hidden="true">
                  <path d="M8 4.5A2.5 2.5 0 0 1 10.5 2h3A2.5 2.5 0 0 1 16 4.5V6h1.5A2.5 2.5 0 0 1 20 8.5v10a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 4 18.5v-10A2.5 2.5 0 0 1 6.5 6H8V4.5Zm2 1.5h4V4.5a.5.5 0 0 0-.5-.5h-3a.5.5 0 0 0-.5.5V6Zm-3.5 2a.5.5 0 0 0-.5.5V11h12V8.5a.5.5 0 0 0-.5-.5h-11Zm11.5 5H6v5.5a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 .5-.5V13Z"/>
                </svg>
              </div>
              <div style="margin-top:0.9rem;font-size:1.2rem;font-weight:500;">Traveling</div>
            </div>
            <div>
              <div style="color:#e79b92;">
                <svg viewBox="0 0 24 24" width="52" height="52" fill="currentColor" style="display:inline-block;" aria-hidden="true">
                  <path d="M3 19.5 9.5 7l3.2 4.8 2.8-3.8L21 19.5H3Zm6.5-3.2a1.3 1.3 0 1 0 0-2.6 1.3 1.3 0 0 0 0 2.6Z"/>
                </svg>
              </div>
              <div style="margin-top:0.9rem;font-size:1.2rem;font-weight:500;">Hiking</div>
            </div>
            <div>
              <div style="color:#e79b92;">
                <svg viewBox="0 0 24 24" width="52" height="52" fill="currentColor" style="display:inline-block;" aria-hidden="true">
                  <path d="M4 12a6 6 0 0 1 6-6h4a6 6 0 0 1 0 12h-1.2l1.1 2.2c.2.4 0 .8-.4 1H12a.7.7 0 0 1-.6-.4L10.3 18H10a6 6 0 0 1-6-6Zm6-4a4 4 0 0 0 0 8h4a4 4 0 0 0 0-8h-4Zm9.2 2.5h1.8a1 1 0 1 1 0 2h-1.8v-2Z"/>
                </svg>
              </div>
              <div style="margin-top:0.9rem;font-size:1.2rem;font-weight:500;">Cooking</div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
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
