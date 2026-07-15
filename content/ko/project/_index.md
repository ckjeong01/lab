---
title: 프로젝트
type: landing
sections:
  - block: portfolio
    content:
      title: 프로젝트
      filters:
        folders:
          - project
        exclude_tags:
          - 완료
    design:
      columns: 2
      view: card
      sort_by: weight
      sort_ascending: true

  - block: portfolio
    content:
      title: 완료 프로젝트
      filters:
        folders:
          - project
        tags:
          - 완료
    design:
      columns: 2
      view: card
      sort_by: weight
      sort_ascending: true

---