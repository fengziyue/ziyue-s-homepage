---
title: "Landing Page"  # Add a page title.
summary: "Hello!"  # Add a page description.
date: "2019-01-01T00:00:00Z"  # Add today's date.
type: "widget_page"  # Page type is a Widget Page
---

+++
# A Recent Publications section created with the Pages widget.
# This section displays recent blog posts from `content/publication/`.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
# widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false


[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 1
  
  # Choose how many pages you would like to offset by
  offset = 1

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
    exclude_featured = false
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
  [[content.filter_button]]
    name = "Depth Prediction"
    tag = "depth prediction"
  [[content.filter_button]]
    name = "Localization"
    tag = "localization"
  [[content.filter_button]]
    name = "Path Planning"
    tag = "path planning"
  [[content.filter_button]]
    name = "Deep Learning"
    tag = "deep learning"


[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
