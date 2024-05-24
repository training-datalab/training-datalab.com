---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

  - block: markdown
    content:
      title: |
      text: |

          <img src="/tDL_logo.png" style="width: 100px; float: left; margin-right: 30px"> <p align="justify"><font size="3">Desde 2020, nuestro grupo ha sido un punto de encuentro para investigadores en diferentes etapas de su carrera y con distintos trasfondos que comparten un interés común por las aplicaciones de la ciencia de datos en las ciencias sociales y las humanidades en tres áreas interconectadas: minería de datos, modelamiento econométrico y aprendizaje automático e inteligencia artificial.</font></p>
    design:
      columns: '1'
  
  - block: collection
    content:
      title: Proyectos emblemáticos
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
      view: showcase
      columns: '1'

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
      view: compact
      columns: '2'
 
  - block: collection
    content:
      title: Publicaciones destacadas
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '2'

  - block: markdown
    content:
      title: Contacto
      subtitle: "contact@training-datalab.com"
    design:
      columns: '1'

---

