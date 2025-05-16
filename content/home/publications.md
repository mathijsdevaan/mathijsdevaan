+++
# Homepage widget to display your publications.

widget = "pages"
headless = true
active = true
weight = 90

title = "Publications"
subtitle = ""

section_id = "publications"

[content]
  page_type = "publication"
  count = 0
  offset = 0
  order = "desc"

  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false

[design]
  view = 4  # Citation style (change to 3 for card layout, 1 for list)

[design.background]
  # Customize if needed
  # color = "navy"
  # text_color_light = true

[advanced]
  css_style = ""
  css_class = ""
+++
