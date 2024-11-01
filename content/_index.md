---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
        Geert Litjens is full professor of Artificial Intelligence for analysis of medical images in radiology and pathology at Radboud University Medical Center and co-chairs the Computation Pathology Group within the Diagnostic Image Analysis Group. His work focusses on application of modern machine learning methods to oncological pathology. Furthermore, he leads and particaptes in several research project bridging the gap between medical specialties such as in prostate and pancreatic cancer. Last, within the European BIGPICTURE project he leads the work package on artificial intelligence.  
      button:
        text: Download CV
        url: uploads/resume.pdf        
#    design:
#      css_class: dark
#      background:
#        color: black
#        image:
#          # Add your image background to `assets/media/`.
#          filename: li-yang-5h_dMuX_7RE-unsplash.webp
#          filters:
#            brightness: 0.4
#          size: cover
#          position: center
#          parallax: false
#  - block: stats
#    content:
#      items:
#        - statistic: "15"
#          description: |
#            Publications
#        - statistic: "1,000+"
#          description: |
#            Citations
#        - statistic: "78"
#          description: |
#            h-index
#    design:
#      # Section background color (CSS class)
#      css_class: "bg-gray-100 dark:bg-gray-900"
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
#  - block: markdown
#    content:
#      title: 'Welcome 👋'
#      subtitle: ''
#      text: |-
#        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.
#
#        **Specialties:** Analytics & Data, Leadership, Programming, Strategic Planning, Writing & Editing
#    design:
#      columns: '1'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      #spacing:
      #  padding: [0, 0, 0, 0]
  - block: collection
    id: publications      
    content:
      title: Recent Publications
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: citation
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: talk      
    content:
      title: Recent Talks
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: talk
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]    
---
