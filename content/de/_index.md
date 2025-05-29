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
        **Im Mittelpunkt meines Weges steht der Wunsch, einen bedeutenden Einfluss auf das Leben anderer zu nehmen, und dass jeder von uns seine eigenen Stärken, Talente und Qualitäten findet, die wir mit anderen teilen können, um die Menschen um uns herum zu stärken und zu unterstützen. Ich glaube, dass das Erkennen und Nutzen dieser Stärken dazu beiträgt, eine verständnisvollere Gemeinschaft mit größerem Zusammenhalt zu schaffen. Inspiriert von den Worten von Rory Vaden - ***„Du bist in der besten Position, der Person zu dienen, die du einmal warst“*** - sehe ich unsere Schwächen und Erfahrungen nicht als Einschränkungen, sondern als Quellen der Widerstandsfähigkeit und des Wachstums. Indem wir unser wahres Selbst akzeptieren, können wir andere auf ihrem eigenen Weg besser verstehen und unterstützen.**

        **Mein Ziel ist es, einen Raum zu schaffen, in dem sich jeder ermutigt fühlt, seine eigenen Gaben und Talente zu erkennen und zu teilen. Durch Offenheit, Freundlichkeit und gegenseitige Unterstützung können wir das Potenzial in uns selbst und in anderen freisetzen und so eine sinnvolle Reflexion, Verbindung und persönliches Wachstum ermöglichen. Wir gehen diesen Weg gemeinsam, und indem wir unsere Stärken anerkennen, tragen wir zu einer Gemeinschaft bei, in der jede Stimme zählt und in der gemeinsames Wachstum möglich ist. Durch ehrliche Gespräche, ein gemeinsames Ziel und Empathie können wir auf eine verständnisvollere, mitfühlendere Zukunft hinarbeiten.**

        >Damit verbunden ist mein persönlicher Blog, in dem ich Themen erforsche, die mit den Grundsätzen meiner Mission übereinstimmen, nämlich die besten Versionen von uns selbst zu werden. Ich glaube, dass durch Offenheit, Freundlichkeit und gegenseitige Unterstützung jeder sein eigenes Potenzial finden und zur Entwicklung unserer Gemeinschaft beitragen kann. In meinem Blog teile ich inspirierende, unterstützende Inhalte, die uns helfen, unser Potenzial zu entdecken und unsere Reise in Richtung Wachstum und positive Veränderung zu unterstützen. Schließe dich mir an, wenn wir gemeinsam unsere Stärken entdecken und uns gegenseitig dabei unterstützen, die beste Version von uns selbst zu werden und gemeinsam für positive Veränderungen zu wachsen - Schritt für Schritt.

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
