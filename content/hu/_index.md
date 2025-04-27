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
        text: Szakmai Önéletrajzom
        url: uploads/resume.hu.pdf
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
      title: '📚 Küldetésem'
      subtitle: ''
      text: |-
        Az utazásom középpontjában az az őszinte vágy áll, hogy jelentőségteljes hatást gyakoroljak mások életére.  Hiszek abban, hogy minden embernek vannak egyedi erősségei—tehetségek és olyan tulajdonságok, melyeket megosztva felemelhetjük és támogathatjuk a körülöttünk élőket. Ezeknek az erősségeknek a felismerése és kihasználása segít egy megértőbb és összetartóbb közösség felépítésében.

        Rory Vaden szavai által inspirálva — **„ Te vagy a legjobb helyzetben ahhoz, hogy azt a személyt szolgáld, aki valaha voltál ”** — a sebezhetőségünket és tapasztalatainkat nem korlátoknak, hanem az ellenálló képesség és a növekedés forrásainak tekintem. Ha elfogadjuk valódi önmagunkat, akkor jobban megérthetünk és támogathatunk másokat a saját útjukon.

        Célom, hogy olyan teret biztosítsak, ahol mindenki bátorítva érzi magát, hogy felismerje és megossza saját adottságait, ajándékait. A nyitottság, a kedvesség és a kölcsönös támogatás révén fel tudjuk szabadítani a bennünk és az azokban rejlő lehetőségeket is, akiket igyekszünk szolgálni. Együtt elősegíthetjük az értelmes elmélkedést, a kapcsolódást és az értelmes fejlődést, megmutatva, hogy a növekedés és a pozitív ráhatás lehetősége mindannyiunk számára elérhető.

        Mindannyian együtt járjuk ezt az utat. Erősségeink felismerésével és fejlesztésével hozzájárulunk egy olyan közösséghez, ahol minden hang számít, és ahol a közös fejlődés megvalósítható. Őszinte beszélgetésekkel és közös célokkal egy együttérzőbb és megértőbb jövőért dolgozhatunk.

        Tarts velem, amint felfedezzük és fejlesztjük erősségeinket, támogatva egymást abban, hogy önmagunk legjobb változataivá váljunk. Növekedjünk együtt, és legyünk a pozitív változás előidézői—egyik lépésről a másikra.

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Kiemelt kiadványok
      filters:
        folders:
          - post
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Legutóbbi kiadványok
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
      title: Friss Blog Bejegyzések
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
