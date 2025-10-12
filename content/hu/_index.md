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
        **Az utazásom középpontjában az az őszinte vágy áll, hogy jelentőségteljes hatást gyakoroljak mások életére, és hogy mindenki megtalálja saját erősségeit, tehetségeit, valamint tulajdonságait, melyeket megosztva felemelhetjük és támogathatjuk a körülöttünk élőket. Hiszek abban, hogy ezeknek az erősségek felismerése és kihasználása segít egy megértőbb, összetartóbb közösség felépítésében. Rory Vaden szavai által inspirálva - ***„Te vagy a legjobb helyzetben ahhoz, hogy azt a személyt szolgáld, aki valaha voltál”*** - a sebezhetőségünket és tapasztalatainkat nem korlátoknak, hanem az ellenálló képesség és a növekedés forrásainak tekintem. Ha elfogadjuk valódi önmagunkat, jobban megérthetünk és támogathatunk másokat saját útjukon.**

        **Célom, hogy olyan teret biztosítsak, ahol mindenki bátorítva érzi magát, hogy felismerje és megossza saját adottságait, ajándékait. A nyitottság, a kedvesség és a kölcsönös támogatás révén felszabadíthatjuk a bennünk és másokban rejlő lehetőségeket is, ezzel elősegítve az értelmes elmélyülést, a kapcsolódást és a személyes fejlődést. Együtt járunk ezen az úton, és az erősségeink felismerésével hozzájárulunk egy olyan közösséghez, ahol minden hang számít, és ahol a közös növekedés megvalósítható. Őszinte beszélgetésekkel, közös célokkal és empátiával dolgozhatunk egy megértőbb, együttérzőbb jövőért.**

        >Ehhez kapcsolódik személyes blogom is, ahol olyan témákat dolgozok fel, melyek összhangban állnak küldetésem alapelveivel, különösen azzal, hogy önmagunk legjobb változataivá váljunk. Hiszem, hogy a nyitottság, a kedvesség és a kölcsönös támogatás révén mindenki megtalálhatja saját lehetőségeit, és hozzájárulhat közösségünk fejlődéséhez. Blogomban inspiráló, támogató tartalmakat osztok meg, melyek segítenek felfedezni a bennünk rejlő potenciált, támogatva ezzel utunkat a növekedés és a pozitív változás felé. Tarts velem, miközben közösen fedezzük fel erősségeinket, támogatva egymást, hogy önmagunk legjobb változataivá váljunk, és együtt növekedjünk a pozitív változásért - lépésről lépésre.

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
