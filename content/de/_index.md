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
        text: Professionellen Lebenslauf
        url: uploads/resume.de.pdf
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
      title: '📚 Meine Mission'
      subtitle: ''
      text: |-
        Im Mittelpunkt unserer gemeinsamen Reise steht der unnachgiebige Wunsch, die Welt um uns herum zu verbessern. Meine Mission wurzelt in der Überzeugung, dass Weisheit in Demut gedeiht und dass die tiefgreifendsten Erkenntnisse über das Leben wirklich transformativ werden, wenn sie mit Freundlichkeit und Offenheit geteilt werden.

        Ich möchte einen Raum schaffen, in dem wir gemeinsam die Komplexität der Existenz erforschen können, indem wir Verletzlichkeit und Stärke gleichermaßen zulassen. Indem ich meine Erfahrungen, meine Perspektiven und mein gesammeltes Wissen mit anderen teile, hoffe ich, dich zum Nachdenken, zum Wachsen und zu sinnvollen Verbindungen anzuregen: Lass uns gemeinsam eine Gemeinschaft kultivieren, die auf Empathie und Verständnis beruht, in der jede Stimme zählt und jede Geschichte die Kraft hat, Veränderungen zu bewirken. Durch ehrlichen Dialog und gemeinsames Lernen können wir den Weg für eine hellere, mitfühlendere Zukunft ebnen.

        Begleite mich auf dieser Entdeckungs- und Erleuchtungsreise, auf der wir uns bemühen, den Weg zu einer besseren Welt zu erhellen, einem Erkenntnis nach dem anderen.

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Ausgewählte Veröffentlichungen
      filters:
        folders:
          - post
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Neueste Veröffentlichungen
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
      title: Neueste Blog Einträge
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
      # Choose a layout view
      view: article-grid
      columns: 3

---
