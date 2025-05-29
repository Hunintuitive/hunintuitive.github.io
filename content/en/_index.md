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
        **At the core of my journey is a genuine desire to make a meaningful impact in the lives of others, and for each of us to find our own strengths, talents and qualities that we can share to uplift and support those around us. I believe that recognising and harnessing these strengths helps to build a more understanding, cohesive community. Inspired by the words of Rory Vaden - ***"You are most powerfully positioned to serve the person you once were"*** - I see our vulnerabilities and experiences not as limitations, but as sources of resilience and growth. By accepting our true selves, we can better understand and support others in their own journeys.**

        **My aim is to provide a space where everyone feels encouraged to recognise and share their own gifts and talents. Through openness, kindness and mutual support, we can unlock the potential within ourselves and others, facilitating meaningful reflection, connection and personal growth. We walk this journey together, and by recognising our strengths, we contribute to a community where every voice counts and where shared growth is possible. Through honest conversations, shared purpose and empathy, we can work towards a more understanding, compassionate future.**

        >Linked to this is my personal blog, where I explore topics that are in line with the principles of my mission, in particular to become the best versions of ourselves. I believe that through openness, kindness and mutual support, everyone can find their potential and contribute to the development of our community. In my blog, I share inspiring, supportive content that helps us discover our potential, supporting our journey towards growth and positive change. Join me as we discover our strengths together, supporting each other to become the best versions of ourselves, and grow together for positive change - step by step.

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
