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

          <img src="/tDL_logo.png" style="width: 150px; float: left; margin-right: 30px"> <p align="justify"><font size="3">Since 2020, our group has been a meeting point for researchers at different career stages and with various backgrounds who share a common interest in the applications of data and computational social science in three interconnected areas: <strong>data mining</strong>, <strong>econometric modelling</strong>, and <strong>machine learning and artificial intelligence</strong>.</font></p>

          <p align="justify"><font size="3">Our mission is to foster collaboration and the exchange of ideas in computational social science to <strong>foster research</strong> and <strong>disseminate specific knowledge and techniques to wider audiences</strong>. Our commitment to open science leads us to promote transparency and open access to our data, results, and processes in order to generate effective solutions to current challenges and foster a positive impact on society.</font></p>
    design:
      columns: '1'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

  - block: markdown
    content:
      title: Flagship Project
      text: |

          <h2>Chilean Political Science Ranking</h2>

          <h3>Chilean Political Science Ranking</h3>

          [<h3>Chilean Political Science Ranking</h3>](/cps-ranking)

          <img src="/cps-ranking.png" style="width: 150px; float: right; margin-left: 30px"> <p align="justify"> <p align="justify"><font size="2.5">This ranking of political science in Chile is one of our flagship projects. It presents a group of researchers at different stages of their careers ordered by H-index and uses the number of accumulated citations as a tie-breaker. It is based on Google Scholar and will soon be five years old with quarterly time series.</font></p>
    design:
      columns: '2'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

  - block: collection
    content:
      title: Flagship Project
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
      title: Recent News
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
      title: Featured Publications
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
      subtitle: "contact@training-datalab.com <br> [Subscribe to our quarterly newsletter](https://zcmp.eu/e28J)"
    design:
      columns: '1'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

---

