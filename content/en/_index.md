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
      title: 'Learning, Growing, and Connecting with Others'
      subtitle: ''
      text: |-
        > A space to share my journey, experiences, and the lessons I’ve gathered along the way - in the hope that they may inspire and support others on their own paths.

        > This site is a space for practice and reflection. Many of the ideas shared here are considered true for the moment, yet I accept that nothing -- and no one -- is infallible. My own imperfections, gaps in understanding, and evolving perspective are part of what is presented. These pages are not meant as final conclusions, but as part of an ongoing process of learning, exploring, and refining thought.
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
      title: '🎯 My Mission'
      subtitle: ''
      text: |-
        >I learn openly, grow intentionally, and amplify what truly helps.

        **My mission is simple: to learn, to grow, and to pass forward whatever wisdom might help someone else. I believe that each of us carries strengths, experiences, and gifts that can uplift the people around us - and when we share them with honesty and kindness, communities become stronger and more compassionate.**

        >Inspired by Rory Vaden’s words, “You are most powerfully positioned to serve the person you once were,” I see our struggles not as weaknesses, but as sources of resilience and insight. The things we’ve lived through can become bridges of understanding for others on similar paths.

        **I don’t seek to reinvent the wheel. Instead, I observe, listen, and reflect. When I encounter ideas, perspectives, or voices that genuinely help me grow, I feel called to amplify them - so their value can reach beyond me and support others as well.**

        **I want to create a space where people feel encouraged to recognise their own strengths, to explore their potential, and to share their unique talents. Through openness, empathy, and mutual support, we can foster genuine connection and meaningful personal growth. We walk this journey together, learning from one another and building a community where every voice matters.**

        >My personal blog is a part of this mission. There, I reflect on growth, healing, self-awareness, and becoming the best version of ourselves. I share what I’m learning -step by step- with the hope that it brings clarity, encouragement, or comfort to someone who needs it.

        **If you feel drawn to this path of honest reflection and shared growth, you’re warmly invited to walk it with me. Together, we discover our strengths and support each other in becoming the best versions of ourselves.**

    design:
      columns: '1'
  - block: markdown
    content:
      title: 'AI and the Writing Process'
      subtitle: ''
      text: |-
        AI has become part of how I work on this website. I use an AI assistant as a tool for thinking, exploration, drafting, translation, and editing. It helps me turn quickly formed thoughts into structured writing, examine ideas from different angles, challenge my assumptions, and refine what I want to express.

        The AI does not determine what I believe or what I want to say. The questions, convictions, interpretations, direction of each article, and final editorial decisions are my own. I also do not treat AI as an authority. Its suggestions are something to examine, question, and, where appropriate, verify.

        I mention this because I believe transparency matters. AI has made it possible for me to bring thoughts into a more coherent and useful form in a way that would otherwise be much harder to sustain alongside everything else in life. My aim is not simply to produce more content, but to take the thoughts and insights I find worth sharing, examine them carefully, and make them as useful and thoughtful as I can for others.

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
