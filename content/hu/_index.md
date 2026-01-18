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
      title: 'Tanulás, fejlődés és kapcsolódás másokkal'
      subtitle: ''
      text: |-
        > Egy hely, ahol megoszthatom az utamat, tapasztalataimat és az útközben szerzett tanulságokat - abban a reményben, hogy másokat is inspirálhatnak és támogathatnak a saját útjukon.

        > Ez az oldal a gyakorlás és a reflexió helyszíne. Az itt megosztott gondolatok többsége jelenleg igaznak tekinthető, azonban elfogadom, hogy semmi -- és senki -- nem tévedhetetlen. Saját tökéletlenségeim, ismereteim hiányosságai és fejlődő szemléletmódom is része annak, amit itt bemutatok. Ezek az oldalak nem végleges következtetéseket tartalmaznak, hanem egy folyamatos tanulási, kutatási és gondolkodási folyamat részét képezik.
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
      title: '🎯 Küldetésem'
      subtitle: ''
      text: |-
        >Nyíltan tanulok, tudatosan fejlődök, és felerősítem azt, ami valóban segít.

        **Küldetésem egyszerű: tanulni, növekedni, és továbbadni mindazt a bölcsességet, ami mások számára is segítséget jelenthet. Hiszem, hogy mindannyiunkban vannak olyan erősségek, tapasztalatok és ajándékok, amelyek képesek felemelni másokat - és amikor ezeket őszintén, kedvesen és nyitottan osztjuk meg, közösségeink erősebbé és együttérzőbbé válnak.**

        >Rory Vaden szavai nagyon inspirálóak: „Te vagy a legjobb helyzetben ahhoz, hogy azt a személyt szolgáld, aki valaha voltál” Úgy látom, hogy a nehézségeink és sebezhetőségünk nem gyengeség, hanem olyan tapasztalat, melyből kitartás, megértés és bölcsesség születik. Amit átélünk, az hidat teremthet mások számára, akik hasonló úton járnak, segítve őket a megértésben és az előrehaladásban.

        **Nem akarom újra feltalálni a kereket. Inkább megfigyelek, hallgatok és gondolkodom. Ha olyan ötletekkel, nézőpontokkal vagy véleményekkel találkozom, amelyek valóban segítenek a fejlődésben, akkor úgy érzem, hogy ezeket tovább kell adnom, hogy azok értéke túlmutasson rajtam, és másokat is támogasson.**

        **Szeretnék olyan teret létrehozni, ahol mindenki bátorítást kap arra, hogy felismerje saját erősségeit, felfedezze a benne rejlő lehetőségeket, és megossza saját tehetségét. Nyitottságon, empátián és kölcsönös támogatáson keresztül valódi kapcsolat és értelmes személyes fejlődés születhet. Ezen az úton együtt haladunk, tanulva egymástól, és olyan közösséget építve, ahol minden hang számít.**

        >A személyes blogom is ennek a küldetésnek a része. Ebben a növekedésről, a gyógyulásról, az önismeretről és arról elmélkedem, hogyan válhatunk önmagunk legjobb változatává. Lépésről lépésre osztom meg, amit tanulok abban a reményben, hogy ez tisztánlátást, bárorítást vagy vígaszt nyújt azoknak, akiknek szükségük van rá.

        **Ha téged is vonz ez az őszinte, közös fejlődésre épülő út, szeretettel hívlak meg, hogy tarts velem. Fedezzük fel együtt a bennünk rejlő erőt, és támogassuk egymást abban, hogy önmagunk legjobb változataivá válhassunk.**

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
