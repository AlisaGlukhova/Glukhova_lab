---
# Leave the homepage title empty to use the site title

title:
date: 2026-09-04
type: landing
sections:
  - block: hero
    content:
      title: |
        Glukhova Lab
      image:
        filename: welcome.jpg
      text: |
        <br>

        We use cryo-electron microscopy to determine high-resolution structures of membrane proteins and protein complexes relevant to human disease.

        Based at the WEHI, Melbourne, Australia.

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
