---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/Huijie-Yang-CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '🔬 Research'
      subtitle: ''
      text: |-
        I am a Ph.D. student in Integrated Biomedical Sciences at UT Health Science Center San Antonio, working with Dr. Yu Luan. My research integrates computational biology and multi-omics approaches to study how genetic variation, epigenomic regulation, and three-dimensional chromatin organization shape disease mechanisms.

        Current projects focus on hepatocellular carcinoma tumor microenvironment dynamics, aging-related myeloid cell responses, and functional characterization of pancreatitis risk variants. I am passionate about bridging statistical genetic findings with molecular mechanisms through integrative genomics.

        Please feel free to reach out for collaboration.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Presentations & Posters
      filters:
        folders:
          - events
    design:
      view: card
      # Show the full poster in the card (no aggressive crop). Uses Fit + object-contain.
      fill_image: false
---
