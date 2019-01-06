+++
# Hero Carousel widget.
widget = "hero_carousel"
active = true
date = 2017-10-15T00:00:00

# Order that this section will appear in.
weight = 6

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.

[[item]]
  title = "A lovely tour"
  content = "Visited Munnar hill station :heart:"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "tour.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "January 1st, 2019"
  cta_url = "img/tour.jpg"

[[item]]
  title = "ACM ICPC"
  content = "The 2018 ICPC Asia Amritapuri Doublesite Regional Contest"
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "icpc.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "December 29th, 2018"
  cta_url = "img/icpc.jpg"
  #cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  title = "Placements @ IIT(BHU)"
  content = "Placed in Microsoft(Software Engineer) :smile:"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "placed.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "December 1st, 2018"
  cta_url = "img/placed.jpg"


+++
