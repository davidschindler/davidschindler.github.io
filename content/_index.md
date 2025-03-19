---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV David Schindler.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: test.png
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: collection
    id: research
    content:
      title: 'Publications'
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      columns: 1
  - block: collection
    id: software
    content:
      title: 'Companian Papers to Software'
      count: 0
      filters:
        folders:
          - software
        featured_only: false
    design:
      view: citation
      columns: 1
  - block: collection
    id: papers
    content:
      title: 'Work in Progress'
      count: 0
      filters:
        folders:
          - workingpapers
        featured_only: false
    design:
      view: citation
      columns: 1
  - block: collection
    id: retired
    content:
      title: 'Retired Papers'
      filters:
        folders:
          - retiredpapers
        featured_only: false
    design:
      view: citation
      columns: 1
  - block: markdown
    id: software
    content:
      title: Software
      text: |
        I have been involved in the development of **μCap (muCap)**, a software tool that enables researchers to link z-Tree and Noldus FaceReader™. The tool can be used free of charge, but we require to be cited.

        Please visit the [μCap website](http://mucap.david-schindler.de/) for further information on μCap and the terms of use.
---
