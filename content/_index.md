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
    id: bio
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
  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: markdown
    id: papers
    content:
      title: Publications
      text: |-
        <div style="max-width:76rem;margin:0 auto;font-size:0.95rem;line-height:1.6;">
        <p style="margin:0 0 0.85rem 0;font-size:0.9rem;color:#fff;"><em>* equal contribution</em></p>
        
        - Neural differential equations for modeling dynamical systems in life sciences. <u><strong>Cecilia Casolo*</strong></u>, Nora Schneider*, Konstantin Hess, Samuel Holt, Mihaela van der Schaar, Stefan Feuerriegel, Niki Kilbertus. Submitted to Nature Methods, 2026.
        - Identifiability Challenges in Sparse Linear Ordinary Differential Equations. <u><strong>Cecilia Casolo</strong></u>, Soren Becker, Niki Kilbertus. ICLR 2026.
        - Signature Kernel Conditional Independence Tests in Causal Discovery for Stochastic Processes. <u><strong>Cecilia Casolo*</strong></u>, Georg Manten*, Emilio Ferrucci, Soren Wengel Mogensen, Cristopher Salvi, Niki Kilbertus. <strong>Spotlight at ICLR 2025</strong>.
        - Uncertainty-Aware Optimal Treatment Selection for Clinical Time Series. Thomas Schwarz, **Cecilia Casolo**, Niki Kilbertus. <strong>Oral</strong> at CRL Workshop at NeurIPS 2024.
        - Your Assumed DAG Is Wrong and Here's How to Deal with It. Kirtan Padh, Zhufeng Li, **Cecilia Casolo**, Niki Kilbertus. CLeaR 2024.
        - An Asymmetric Independence Model for Causal Discovery on Path Spaces. Georg Manten, **Cecilia Casolo**, Soren Wengel Mogensen, Niki Kilbertus. CLeaR 2024.
        - Learning Counterfactually Invariant Predictors. <u><strong>Cecilia Casolo*</strong></u>, Francesco Quinzan*, Krikamol Muandet, Yucen Luo, Niki Kilbertus. TMLR 2024.
        
        </div>
    design:
      columns: '1'
  - block: markdown
    id: talks
    content:
      title: Talks, Workshop, Outreach
      text: |-
        <div style="max-width:76rem;margin:0 auto;font-size:0.95rem;line-height:1.6;">
        
        - **Uncertainty-Aware Optimal Treatment Selection for Clinical Time Series**. Causal Representation Learning Workshop at NeurIPS 2024, Vancouver, Canada, December 2024.
        - **Causal Discovery in Dynamical Systems**. UAI 2024 Workshop, Barcelona, Spain, July 2024.
        - Co-organizer of <a href="https://collab.dvb.bayern/spaces/TUMmathstat/pages/574095571/CAUSE+Junior+Researcher+Day+Spring+2024">CAUSE workshop at TUM 2024</a>.
        - **Signature Kernel Conditional Independence Tests in Causal Discovery for Stochastic Processes**. Rough Path Interest Group, University of Oxford, Oxford, United Kingdom, April 2024.
        - **Learning Counterfactually Invariant Predictors**. TUM CAUSE Seminar, Munich, Germany, November 2023.
        - **Causal Machine Learning**. Konrad Zuse Schools Opening Event, Germany, October 2023.
        - **Poster Presentations at MLSS Krakow and ELLIS Doctoral Symposium**. MLSS Krakow 2023 and ELLIS Doctoral Symposium 2023, Europe, July 2023.
        - Co-organizer of <a href="https://sites.google.com/view/caudyn2022/home">A Causal View on Dynamical Systems</a> at NeurIPS 2022.
        - Blog editor for RelAI Blog.
        - Member of <a href="https://zuseschoolrelai.de">Konrad Zuse School of Excellence in Reliable AI</a>.
        
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
