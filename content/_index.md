---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 欢迎来到 SWUFE AGI 团队
        content: 依托西财唯一工科实验室，用大模型技术改变世界...
        align: center
        background:
          image:
            filename: lab.webp
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 科研工作两不误
        content: '顶会/顶刊论文，大厂实习工作，科研项目，学术交流...'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 并肩作战，一起成长 💪
        content: '从真实问题中学习，培养解决问题的能力和团队合作精神'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 加入我们
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2500
  - block: hero
    content:
      title: |
        SWUFE AGI
      image:
        filename: AGI.png
      text: |
        <br>
        
        随着人工智能技术的不断发展，通用人工智能（Artificial General Intelligence, AGI）和金融领域的融合与交叉已成为科研和产业发展的重要趋势。通用人工智能与金融创新团队致力于通过大模型探索AGI技术在金融领域的应用潜力，以及推动人工智能技术与金融行业的创新发展。 
  
  - block: collection
    content:
      title: 团队动态
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="研究团队 →" %}}
    design:
      columns: '1'
---
