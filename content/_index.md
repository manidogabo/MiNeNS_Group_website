---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: hero
    content:
      title: |

        <span style="color:#C41230">**M**</span>echanically 
        <span style="color:#C41230">**In**</span>telligent 
        <span style="color:#C41230">**En**</span>gineered 
        <span style="color:#C41230">**S**</span>tructures 
        <span style="color:#C41230">**Lab**</span>oratory 
      image:
        filename: welcome.jpg
      text: |
        The 
        <span style="color:#C41230">**MInEnS Lab**</span> 
        aims to transform simple mechanical inputs into the complex assembly and control of materials. To this end we work at the intersection of fluid flow, flexible structures, and design to  research, teaching, and practice since its founding in 2016.
  
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
  

  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---