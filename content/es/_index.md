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

          <img src="/tDL_logo.png" style="width: 100px; float: left; margin-right: 30px"> <p align="justify"><font size="3">Desde 2020, nuestro grupo ha sido un punto de encuentro para investigadores en diferentes etapas de su carrera y con distintos trasfondos que comparten un interés común por las aplicaciones de la ciencia de datos y computacional en ciencias sociales en tres áreas interconectadas: **minería de datos**, **modelamiento econométrico** y **aprendizaje automático e inteligencia artificial**.</font></p>
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
      title: Proyectos relevantes
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
      title: Noticias recientes
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
      title: Publicaciones destacadas
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
      title: Contacto
      subtitle: contact
      text: |
          
          <font size="5"><i class="fa-regular fa-envelope"></i> contact@training-datalab.com</font><br>
          <font size="5"><i class="fa-brands fa-github"></i> https://github.com/training-datalab</font><br>
          <font size="5"><i class="ai ai-zenodo-square ai-3x"></i> https://zenodo.org/communities/tdl/</font>
    design:
      columns: '2'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

---

