---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I develop AI methods that help surgeons see and act more precisely. My work spans three connected themes:

        - **Brain tumor analysis in MRI.** Deep learning for glioma segmentation ([DeepSeg](https://github.com/razeineldin/DeepSeg), hybrid vision-transformer/CNN models), with a method that won the MICCAI **BraTS 2022** challenge.
        - **Image-guided neurosurgery.** Registering preoperative MRI to intraoperative ultrasound to compensate for brain shift (iRegNet), and explainable guidance systems such as NeuroIGN.
        - **Surgical robotics and training.** Foundation models for surgical instrument segmentation, natural-language anatomy localization in neuroendoscopy, and speech-based control of surgical robots.

        Across all of these I care about **explainability** ([NeuroXAI](https://github.com/razeineldin/NeuroXAI)) and releasing **open-source tools** such as [Slicer-DeepSeg](https://github.com/razeineldin/Slicer-DeepSeg) for 3D Slicer.

        I'm always happy to discuss collaborations and student projects. Please reach out 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications
      count: 0
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      count: 6
      filters:
        folders:
          - publications
        exclude_featured: true
      archive:
        enable: true
        text: See all publications
        link: publications/
    design:
      view: citation
---
