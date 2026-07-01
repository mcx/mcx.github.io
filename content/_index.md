---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-07-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        I am currently leading a team in developing capabilities for quadruped robots. The focus is on using learning-based methods for perceptual locomotion and terrain-awareness, enabling legged robots to safely and robustly navigate both urban areas and unstructured outdoor environments.

        My research interests lie at the intersection of legged locomotion and reinforcement learning, with the goal of encouraging widespread adoption of robots in society.
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: large
        shape: circle

  - block: collection
    id: publications
    content:
      title: Publications
      text: |
        [Google Scholar](https://scholar.google.com/citations?hl=en&user=iBU4CfIAAAAJ)
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
