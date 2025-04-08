---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
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
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: p6.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="研究团队 →" %}}
    design:
      columns: '1'
---
