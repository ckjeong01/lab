---
# Leave the homepage title empty to use the site title
title: 
date: 2026-06-20
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <div class="under-construction">
        🚧 <strong> 공사 중입니다.</strong> 조만간 다시 들러주세요.
        </div>
    design:
      columns: '1'
      
  - block: hero
    content:
      title: |
        한국 삼대륙 연구 공방
      image:
        filename: welcome.jpg
      text: |
        <br>
        <ul>
        <li>현대 사회 현상과 하위주체성(subalternity)에 대한 비판적 통찰
        <li>탈식민주의적 관점
        <li>다학제적 비교연구 방법
        </ul>
  
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        저희는 성균관대학교(SKKU) 소속의 소규모 연구자 그룹입니다. 식민지 및 탈식민지 역학 관계에 초점을 맞추어 한국과 그 너머의 현대 사회 문제를 연구합니다. 한국 사회의 현상을 포괄적으로 이해하기 위해서는 한국 사회의 뿌리가 제3세계에 있음을 직시하는 것이 매우 중요하다는 인식을 공유합니다. 또한, 한국 사회를 다루는 현대 학계의 미국 및 유럽 중심적 시각을 비판하며, 한국을 탈식민 사회라는 맥락 속에 위치시키는 비교 연구의 틀을 지지합니다. 저희의 관심사는 한국사라는 지역적 한계를 넘어 삼대륙(Tricontinent, 아시아·아프리카·남미)의 다른 지역에서 나타나는 식민지 하위주체성(subalternity) 문제까지 포괄합니다.

        학문적 경계라는 것이 사회적 대상이 본질적으로 가진 경계를 제대로 반영하지 못한다는 전제 하에, 사회 비판에 대한 학제간 융합적 접근을 추구합니다. 저희 연구원들은 인문·사회과학의 전통적인 학문 전반에 걸쳐 훈련을 받았으며, 저희 프로젝트는 사회학, 분석 및 대륙 철학, 문학, 역사학, 정치학의 방법론들을 결합하여 활용합니다.

    design:
      columns: '1'

  - block: collection
    content:
      title: 새 소식
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
        {{% cta cta_link="./people/" cta_text="공방 사람들을 만나보세요. →" %}}
    design:
      columns: '1'
---
