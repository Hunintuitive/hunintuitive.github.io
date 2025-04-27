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
        Im Mittelpunkt meines Weges steht der aufrichtige Wunsch, im Leben anderer Menschen Gutes zu bewirken.  Ich glaube, dass jeder Mensch einzigartige Stärken hat - Talente und Eigenschaften, die, wenn sie geteilt werden, die Menschen um uns herum erheben und unterstützen können. Diese Stärken zu erkennen und zu nutzen hilft, eine verständnisvollere und eng verbundene Gemeinschaft aufzubauen.

        Inspiriert von Rory Vadens Worten - **"Du bist am stärksten in der Lage, der Person zu dienen, die du einmal warst "** - sehe ich unsere Schwachstellen und Erfahrungen nicht als Hindernisse, sondern als Quellen der Widerstandsfähigkeit und des Wachstums. Wenn wir unser authentisches Selbst akzeptieren, können wir andere auf ihrem eigenen Weg besser verstehen und unterstützen.

        Mein Ziel ist es, einen Raum zu schaffen, in dem sich jeder ermutigt fühlt, seine eigenen Gaben zu erkennen und mit anderen zu teilen. Durch Offenheit, Freundlichkeit und gegenseitige Unterstützung können wir das Potenzial freisetzen - sowohl in uns selbst als auch in denen, denen wir dienen. Gemeinsam können wir Reflexion, Verbindung und sinnvollen Fortschritt fördern und zeigen, dass Wachstum und positiver Einfluss in der Reichweite eines jeden liegen.
 
        Wir sitzen alle im selben Boot. Indem wir unsere Stärken erkennen und kultivieren, tragen wir zu einer Gemeinschaft bei, in der jede Stimme zählt und gemeinsamer Fortschritt möglich ist. Durch ehrliche Gespräche und gemeinsame Ziele können wir auf eine mitfühlendere und verständnisvollere Zukunft hinarbeiten.

        Schließe dich mir an, während wir unsere Stärken erforschen und entwickeln und uns gegenseitig dabei unterstützen, die besten Versionen von uns selbst zu werden. Lass uns gemeinsam wachsen und einen positiven Unterschied machen – einen Schritt nach dem anderen.

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
