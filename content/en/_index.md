---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <div class="under-construction">
        🚧 <strong>This site is currently under construction.</strong> Please check back soon.
        </div>
    design:
      columns: '1'
      
  - block: hero
    content:
      title: |
        Korea Tricontinent Research Atelier
      image:
        filename: welcome.jpg
      text: |
        <br>
         Comparative and postcolonial research group providing critical, interdisciplinary insights into contemporary social phenomena and subalternity.
  
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        We are a small group of researchers at Sungkyunkwan University (SKKU) located in Seoul, South Korea. We are interested in studying contemporary social problems in Korea and beyond with special focus on colonial/postcolonial dynamics. We share the perception that confronting the Third World origins of South Korean society is crucial for achieving a comprehensive understanding of its phenomena. We are critical of the US- and Eurocentric vision of contemporary scholarship on Korean society and advocate a comparative framework that places it within the context of postcolonial societies. Our interests also extend beyond the regional confines of Korean history to colonial subalternity manifested in other parts of the Tricontinent. 
        
        We strive for an interdisciplinary approach to social critique based on the assumption that disciplinary demarcations only weakly track boundaries that exist in the nature of social objects. Our members are trained across traditional disciplines in the human sciences, and our projects combine tools from sociology, analytic and continental philosophy, literature, history, and political science. 

    design:
      columns: '1'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
