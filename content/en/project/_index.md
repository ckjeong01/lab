---
title: Projects
type: landing
sections:
  - block: portfolio
    content:
      title: Projects
      filters:
        folders:
          - project
        exclude_tags:
          - completed
    design:
      columns: 2
      view: card
      sort_by: weight
      sort_ascending: true

  - block: portfolio
    content:
      title: Past Projects
      filters:
        folders:
          - project
        tags:
          - completed
    design:
      columns: 2
      view: card
      sort_by: weight
      sort_ascending: true
---