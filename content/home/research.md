---

widget: slider # See https://wowchemy.com/docs/page-builder/
headless: false # This file represents a page section.
weight: 20 # Order that this section will appear.
active: true
design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: 1000px
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 3000

content:
  slides:
    - title: The Kriegstein Lab
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: better_lab_photo.jpg
        fit: cover
    - title: Cortical Organoids
      content: 'Cortical Organoids from human stem cells'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: organoid.png
        fit: cover
    - title: Join us!!
      content: ''
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.7
        media: ParnassusRMB.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---