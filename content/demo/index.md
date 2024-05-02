---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Intra-fractional motion modeling
        content: 
        align: center
        background:
          image:
            filename: intra-cor.gif
            filters:
              brightness: 0.7
          position: right
      - title: Inter-fractional anatomic changes
        content: 
        align: left
        background:
          image:
            filename: inter-cor.gif
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Large anatomic deformation caused by posture different (upright vs supine)
        content: 
        align: right
        background:
          image:
            filename: upright-sag.gif
            filters:
              brightness: 0.5
          position: center
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      css: "width:50%;"
      slide_width: "50%"
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
