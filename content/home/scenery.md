---
widget: slider # Use the Slider widget as this page section
weight: 20 # Position of this section on the page
active: true # Publish this section?
headless: true # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ""
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - align: center
      background:
        media: albums/scenery/field_trail.jpg
        fit: cover
    - align: center
      background:
        media: albums/scenery/overlook.jpg
        fit: cover
    - align: center
      background:
        media: albums/scenery/river_bridge.jpg
        fit: cover
    - align: center
      background:
        position: center
        media: albums/scenery/river_sun.jpg
        fit: cover
---
