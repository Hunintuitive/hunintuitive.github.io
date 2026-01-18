---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-27
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: 'Lernen, Wachsen und Verbindungen schaffen'
      subtitle: ''
      text: |-
        > Ein Raum, in dem ich meine Reise, Erfahrungen und Erkenntnisse teile - in der Hoffnung, andere auf ihrem eigenen Weg zu inspirieren und zu unterstützen.

        > Diese Website ist ein Ort zum Üben und Nachdenken. Viele der hier geteilten Ideen gelten derzeit als wahr, doch ich bin mir bewusst, dass nichts -- und niemand -- unfehlbar ist. Meine eigenen Unvollkommenheiten, Wissenslücken und sich weiterentwickelnden Perspektiven sind Teil dessen, was hier präsentiert wird. Diese Seiten sind nicht als endgültige Schlussfolgerungen gedacht, sondern als Teil eines fortlaufenden Prozesses des Lernens, Erforschens und Verfeinerns von Gedanken.
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
      title: '🎯 Meine Mission'
      subtitle: ''
      text: |-
        >Ich lerne offen, wachse bewusst und verstärke das, was wirklich hilft.

        **Meine Mission ist einfach: zu lernen, zu wachsen und das weiterzugeben, was anderen vielleicht helfen kann. Ich glaube, dass jeder von uns Stärken, Erfahrungen und einzigartige Gaben in sich trägt, die andere Menschen bereichern können - und dass Gemeinschaften stärker und mitfühlender werden, wenn wir diese Dinge ehrlich und offen miteinander teilen.**

        >Die Worte von Rory Vaden begleiten mich: „Du bist in der besten Position, der Person zu dienen, die du einmal warst“ Für mich sind unsere Verletzlichkeiten und Herausforderungen keine Schwächen, sondern Quellen für Verständnis, Widerstandskraft und persönliches Wachstum. Das, was wir erlebt haben, kann eine Brücke für diejenigen sein, die ähnliche Wege gehen, und ihnen zu einem besseren Verständnis und mehr Einsicht verhelfen.

        **Ich versuche nicht, das Rad neu zu erfinden. Stattdessen beobachte, höre zu und denke nach. Wenn ich auf Ideen, Perspektiven oder Stimmen stoße, die mir wirklich helfen, mich weiterzuentwickeln, fühle ich mich dazu berufen, sie zu verbreiten - damit ihr Wert über mich hinausgeht und auch anderen zugute kommt.**

        **Ich möchte einen Raum schaffen, der dazu ermutigt, die eigenen Stärken zu erkennen, das eigene Potenzial zu entfalten und die persönlichen Talente mit anderen zu teilen. Durch Offenheit, Empathie und gegenseitige Unterstützung können echte Verbundenheit und bedeutungsvolles Wachstum entstehen. Wir gehen diesen Weg gemeinsam, lernen voneinander und bauen eine Gemeinschaft auf, in der jede Stimme zählt.**

        >Mein persönlicher Blog ist ein Teil dieser Mission. Dort reflektiere ich über Wachstum, Heilung, Selbstbewusstsein und darüber, wie wir die beste Version unserer selbst werden können. Ich teile Schritt für Schritt, was ich lerne, in der Hoffnung, dass es jemandem, der es braucht, Klarheit, Ermutigung oder Trost bringt.

        **Wenn dich dieser Weg der ehrlichen Reflexion und des gemeinsamen Wachstums anspricht, lade ich dich herzlich ein, ihn mit mir zu gehen. Gemeinsam entdecken wir unsere Stärken und unterstützen uns darin, zu der besten Version unserer selbst zu werden.**

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
