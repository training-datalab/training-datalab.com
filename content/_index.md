---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      image:
        filename: code.jpg
      text: |

         <img src="/tDL_logo.png" style="width: 150px; float: left; margin-right: 30px"> <p align="justify"><font size="3">Nuestro grupo de investigación se enfoca en aplicaciones de ciencia de datos en ciencias sociales en tres áreas interconectadas: minería de datos, modelamiento econométrico y aprendizaje automático. Por una parte, buscamos recoger datos con técnicas de minería para elaborar modelos econométricos con técnicas observacionales o de emparejamiento.</font></p> 
  
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
      title: Financiamiento y apoyo
      text: '<img src="/leiden.png" style="width: 150px"> &nbsp; <img src="/udp.png" style="width: 150px"> &nbsp; <img src="/oxford.jpg" style="width: 55px"> &nbsp;&nbsp; <img src="/usach.png" style="width: 50px"> &nbsp;&nbsp;&nbsp; <img src="/umayor.png" style="width: 55px"> &nbsp;&nbsp; <img src="/anid.png" style="width: 55px">'
    design:
      columns: '1'

  - block: markdown
    content:
      title: Contacto
      subtitle: "contact@training-datalab.com"
    design:
      columns: '1'

---

