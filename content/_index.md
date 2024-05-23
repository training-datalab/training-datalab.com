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
        filename: tDL_logo.png
      text: |
        <br>

        <img src="tDL_logo.png" style="width: 150px, float: left; border: 10px"> <p align="justify"><font size="3">Este grupo de investigación se enfoca en aplicaciones de ciencia de datos en ciencias sociales en tres áreas interconectadas: minería de datos, modelamiento econométrico y aprendizaje automático. Por una parte, buscamos recoger datos con técnicas de minería para elaborar modelos econométricos con técnicas observacionales o de emparejamiento.</font></p>

        <p align="justify"><font size="3">Por otro lado, nos enfocamos en entrenar modelos con técnicas de aprendizaje automático y profundo etiquetando conjuntos de datos para diferentes proyectos. Lo anterior, nos permite clasificar datos no codificados usando nuestros modelos entrenados incorporando validación humana en el flujo de trabajo, lo que mejora la inteligencia artificial en los procesos de aprendizaje.</font></p>
  
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

  - block: contact
    content:
      title: Contacto
      subtitle: "contact@training-datalab.com"
    design:
      columns: '1'

---

