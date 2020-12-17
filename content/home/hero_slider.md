---
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...
weight: 10  # Order that this section will appear.
title: "Gruen Laboratory"
subtitle: "Unravelling the genetics of reading"

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: calc(100vh - 70px)


item:
  - title: Bike photo
    overlay_color: '#666'  # An HTML color value.
    overlay_img: "heros/pages.jpg"  # Image path relative to your `static/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
  - title: Pages photo
    overlay_color: '#666'  # An HTML color value.
    overlay_img: "heros/bike_group.color.jpeg"  # Image path relative to your `static/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
  - title: Cells photo
    overlay_color: '#666'  # An HTML color value.
    overlay_img: "heros/purple_cells.jpg"  # Image path relative to your `static/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.

advanced:
  css_class: "home-jumbotron"
---
{{< button text="Learn more" url="#about-us">}}
