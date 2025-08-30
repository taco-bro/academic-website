---
title: 'Notes'
date: 2025-08-30
type: landing

design:
  spacing: '2rem'


# Page sections
sections:
  # - block: markdown
  #   content:
  #     title: ''
  #     subtitle: ''
  #     text: |-
  #   design:
  #     columns: '3'
  - block: collection
    id: notes
    content:
      title: |-
        Notes
      subtitle: '(under construction)'
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        folders:
          - myNotes
        # author: ""
        # category: ""
        # tag: ""
        # exclude_featured: false
        # exclude_future: false
        # exclude_past: false
        # publication_type: ""
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
