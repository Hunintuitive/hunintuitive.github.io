---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Get My Professional CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: coolbackground.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Mission'
      subtitle: ''
      text: |-
        At the heart of our shared journey lies an unyielding desire to better the world around us. My mission is rooted in the belief that wisdom flourishes in humility, and that the most profound insights about life become truly transformative when shared with kindness and openness.

        I aspire to create a space where we can explore the complexities of existence together, embracing vulnerability and strength alike. By sharing my experiences, perspectives, and gleaned knowledge, I hope to inspire others to reflect, grow, and connect in meaningful ways. Together, let us cultivate a community grounded in empathy and understanding, where every voice matters, and every story has the power to spark change. Through honest dialogue and shared learning, we can pave the way for a brighter, more compassionate future.

        Join me on this journey of discovery and enlightenment, as we endeavor to illuminate the path to a better world, one insight at a time.

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - post
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - post
        exclude_featured: true
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: _________
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent Blog Posts
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      view: article-grid
      columns: 3

---
