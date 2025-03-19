---
title: Teaching
summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: markdown
    id: software
    content:
      title: Teaching
      text: |
        Below you will find a list of courses I taught. For some courses, you can download a detailed teaching evaluation (some of those from the University of Munich may be in German only).
  - block: collection
    id: teaching
    content:
      title: At Tilburg University
      count: 0
      filters:
        folders:
          - teaching
    design:
      view: citation
      columns: 1
  - block: collection
    id: teaching2
    content:
      title: At the University of Munich
      count: 0
      filters:
        folders:
          - teachinglmu
    design:
      view: citation
      columns: 1
---
