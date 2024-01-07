---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


gallery_item:
  - album: gallery
    image: balloon-pop.jpg
    caption: Deformation, bursting, and bouncing of water balloons
  - album: gallery
    image: bead-defects.jpg
    caption: Beaded sheets
  - album: gallery
    image: bead-dome.png
    caption: Beaded gridshell based on Chebyshev Nets
  - album: gallery
    image: exp-waterBomb.png
    caption: Time series of a bouncing elastic capsule
  - album: gallery
    image: snake-fall.jpg
    caption: A chain hitting an obstacle
  - album: gallery
    image: bead-patterns.png
    caption: Planar regular polygonal weaves 
  - album: gallery
    image: raspberry.jpg
    caption: An all-in-one soft robotic gripper and muscle
  - album: gallery
    image: wings.jpg
    caption: Cicada wings at various deployment stages

sections:
#   - block: markdown
#     design:
#       columns: '1'
#       background:
#         image: 
#           filename: bead-blur.jpg
#           filters:
#             brightness: 1
#           parallax: false
#           position: center
#           size: cover
#         text_color_light: false
#       spacing:
#         padding: ['0', '0', '1', '0']
#       css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title: |
  #       <span style="color:#C41230">**M**</span>echanically 
  #       <span style="color:#C41230">**In**</span>telligent 
  #       <span style="color:#C41230">**En**</span>gineered 
  #       <span style="color:#C41230">**S**</span>tructures 
  #       <span style="color:#C41230">**Lab**</span>oratory 
  #     subtitle: '<span style="color:white">Carnegie Mellon University</span>'
  #     # text: 
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: bead_defects.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  - block: markdown
    content:
      title: |
        <span style="color:#F3B26D">**M**</span>echanically 
        <span style="color:#F3B26D">**In**</span>telligent 
        <span style="color:#F3B26D">**En**</span>gineered 
        <span style="color:#F3B26D">**S**</span>tructures 
        <span style="color:#F3B26D">**Lab**</span>oratory 
      subtitle: ''
      # image:
      #   filename: bead_defects.jpg
      text: |
        <span style=" background: rgba(0,0,0,.3); padding: 5px"> The <span style="color:#F3B26D">**MInEnS Lab**</span> gets its name from the _Ojibwemowin_ word for bead: _manidoominens_. When going from _Ojibwemowin_ to English, _manidoominens_ is translated as _spirit-seed_. In the spirit of its english acronym, our general aim is to seed technologies that transform simple mechanical inputs into the complex assembly and control of materials. We interact with multiple applications (e.g. soft robotics, architecture, medical devices, roll-to-roll manufacturing) while working at the intersections of interfacial, flexible, granular, and active matter. At our core, the <span style="color:#F3B26D">**MInEnS Lab**</span> is curiosity driven as we aim to develop and disseminate knowledge alongside all technical pursuits.

        {{% cta cta_link="./people/" cta_text="Join Us! →" %}}

        {{< youtube 61HpWDJ1bsw >}}

    design:
      columns: '2'
      background:
        image: 
          filename: bead-blur.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          caption: testing 123
        text_color_light: true
      spacing:
        padding: ['1', '0', '1', '0']
      css_class: fullscreen
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./contact/" cta_text="contact me →" %}}
  #   design:
  #     columns: '1'

  # - block: collection
  #   content:
  #     title: News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        {{< gallery album="gallery" >}}
---