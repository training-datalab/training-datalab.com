---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
      text: |

          <img src="/tDL_logo.png" style="width: 100px; float: left; margin-right: 30px"> <p align="justify"><font size="3">Since 2020, our group has been a meeting point for researchers at different career stages and with various backgrounds who share a common interest in the applications of data and computational social science in three interconnected areas: **data mining**, **econometric modelling**, and **machine learning and artificial intelligence**.</font></p>
    design:
      columns: '1'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'
  
  - block: collection
    content:
      title: Flagship projects
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: 'flagship'
      offset: 0
      order: desc
      page_type: project
    design:
      view: compact
      columns: '2'
      flip_alt_rows: true
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

  - block: collection
    content:
      title: News
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
      view: list
      columns: '2'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'
 
  - block: collection
    content:
      title: Featured publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
        tag: 'wos-article'
    design:
      view: citation
      columns: '2'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

  - block: markdown
    content:
      title: Contact
      subtitle: "contact@training-datalab.com"
    design:
      columns: '1'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

---

