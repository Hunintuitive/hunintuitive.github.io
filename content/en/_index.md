---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-27
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
        At the core of my journey is a sincere desire to make a meaningful difference in the lives of others.  I believe that each person has unique strengths-talents and qualities that, when shared, can uplift and support those around us. Recognizing and leveraging these strengths helps build a more understanding and connected community.

        Inspired by Rory Vaden’s words - **"You are most powerfully positioned to serve the person you once were"** - I see our vulnerabilities and experiences not as obstacles, but as sources of resilience and growth. Embracing our authentic selves allows us to better understand and support others in their own journeys.

        My aim is to create a space where everyone feels encouraged to identify and share their gifts. Through openness, kindness, and mutual support, we can unlock potential-both within ourselves and in those we serve. Together, we can foster reflection, connection, and meaningful progress, demonstrating that growth and impact are within everyone's reach.

        We’re all in this together. By recognizing and cultivating our strengths, we contribute to a community where every voice matters and collective progress is possible. Through honest conversations and shared purpose, we can work toward a more compassionate and understanding future.

        Join me as we explore and develop our strengths, supporting each other in becoming the best versions of ourselves. Let’s grow together and make a positive difference-one step at a time.

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
