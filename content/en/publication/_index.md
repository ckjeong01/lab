---
title: Publications
type: landing
sections:
  # - block: collection
  #   content:
  #     title: Preprint
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: article
  #   design:
  #     view: citation
  #     columns: '1'
  - block: collection
    content:
      title: Journal Articles
      filters:
        folders:
          - publication
        publication_type: article-journal
      sort_by: Date
      sort_ascending: false  # 최신순, true로 하면 오래된 순  
    design:
      view: citation
      columns: '1'
  - block: collection
    content:
      title: Conference Papers
      filters:
        folders:
          - publication
        publication_type: paper-conference
      sort_by: Date
      sort_ascending: false  # 최신순, true로 하면 오래된 순  
    design:
      view: citation
      columns: '1'
---