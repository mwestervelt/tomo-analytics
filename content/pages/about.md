---
title: About Us
hide_title: false
sections:
  - type: content_section
    content: >-
      Lorem Ipsum


      In sollicitudin imperdiet turpis quis accumsan. Pellentesque euismod
      turpis et nisi fermentum accumsan.
    # image: images/about.jpg
    # image_alt: Our team in the meeting room
  - type: grid_section
    section_id: team
    title: The Team
    subtitle: An optional subtitle of the section
    col_number: two
    grid_items:
      - title: Zane Troyer
        image: images/zane.jpeg
        subtitle: 'Co-Founder, Chief Data Scientist'
        content: >-
          Something about leading data science teams, Principal Data Scientist, speaker at 
        actions:
          - label: Linkedin
            url: 'https://www.linkedin.com/in/zane-troyer-72b5a6170/'
            style: icon
            icon: linkedin
            new_window: true
      - title: Mariel Troyer
        image: images/mar.jpeg
        subtitle: 'Co-Founder, CEO'
        content: >-
          Mariel's background in software development and product management, from large enterprise scale to high growth startup, gives her the perfect mix of expertise to lead and influence her clients from both the technical and business perspectives. 
        actions:
          - label: Linkedin
            url: 'https://www.linkedin.com/in/mariel-westervelt/'
            style: icon
            icon: linkedin
            new_window: true
#   - type: cta_section
#     section_id: cta
#     title: Become a Team Player
#     content: >-
#       We are always looking for great people to join our team. If you are
#       interested in working for Agency, please send an email to
#       [email@example.com](mailto:email@example.com) with your CV and which
#       position you are interested in.
#     image: images/cta-about.svg
#     image_alt: Illustration
#     bg_color: light
seo:
  title: About Us
  description: This is the about us page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: About Us
      keyName: property
    - name: 'og:description'
      value: This is the about us page
      keyName: property
    - name: 'og:image'
      value: images/about.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: About Us
    - name: 'twitter:description'
      value: This is the about us page
    - name: 'twitter:image'
      value: images/about.jpg
      relativeUrl: true
layout: advanced
---
