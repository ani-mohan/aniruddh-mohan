---
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Recent publications

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 4
  # Choose how many pages you would like to offset by
  offset: 1
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Choose a view for the listings:
  view: citation
  columns: '2'
---
{{% alert note %}}
You can filter all publications by type and date [here]({{< ref "/publication/_index.md" >}}).
{{% /alert %}}

