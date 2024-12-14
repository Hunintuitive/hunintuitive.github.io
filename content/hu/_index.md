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
        Közös utunk középpontjában az a rendíthetetlen vágy áll, hogy jobbá tegyük a körülöttünk lévő világot. Küldetésem abban a hitben gyökerezik, hogy a bölcsesség alázatban virágzik, és hogy az élet legmélyebb felismerései akkor válnak igazán átalakító erejűvé, ha kedvességgel és nyitottsággal osztjuk meg őket.

        Arra törekszem, hogy olyan teret teremtsek, ahol együtt fedezhetjük fel a létezés összetettségét, a sebezhetőséget és az erőt egyaránt felvállalva. Azzal, hogy megosztom tapasztalataimat, nézőpontjaimat és összegyűjtött tudásomat, remélem, hogy másokat is inspirálni tudok arra, hogy elgondolkodjanak, fejlődjenek és értelmes módon kapcsolódjanak egymáshoz. Építsünk együtt egy olyan közösséget, amelynek alapja az empátia és a megértés, ahol minden hang számít, és minden történetnek megvan az ereje, hogy változást idézzen elő. Az őszinte párbeszéd és a közös tanulás révén kikövezhetjük az utat egy fényesebb, együttérzőbb jövő felé.

        Csatlakozz hozzám ezen a felfedező és megvilágosító utazáson, miközben arra törekszünk, hogy megvilágítsuk az utat egy jobb világ felé, egy-egy felismeréssel lépésenként.

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
