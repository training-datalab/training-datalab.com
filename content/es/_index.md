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

          <img src="/tDL_logo.png" style="width: 150px; float: left; margin-right: 30px"> <p align="justify"><font size="3">Desde 2020, nuestro grupo ha sido un punto de encuentro para investigadores en diferentes etapas de su carrera y con distintos trasfondos que comparten un interés común en las aplicaciones de los datos y las ciencias sociales computacionales en tres áreas interconectadas: <strong>minería de datos</strong>, <strong>modelamiento econométrico</strong> y <strong>aprendizaje automático e inteligencia artificial</strong>.</font></p>

          <p align="justify"><font size="3">Nuestra misión es fomentar la colaboración y el intercambio de ideas en las ciencias sociales computacionales para <strong>impulsar la investigación</strong> y <strong>difundir el conocimiento y técnicas específicas a públicos más amplios</strong>. Nuestro compromiso con la ciencia abierta nos lleva a promover la transparencia y el acceso abierto a nuestros datos, resultados y procesos, con el fin de generar soluciones efectivas para los desafíos actuales y fomentar un impacto positivo en la sociedad.</font></p>
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
      title: Blog
      subtitle: Noticias y columnas
      text:
      count: 3
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
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'
 
  - block: collection
    content:
      title: Publicaciones destacadas
      subtitle: Artículos en revistas científicas
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
      subtitle: "[Síguenos en LinkedIN](http://linkedin.com/company/training-data-lab) <br> contact@training-datalab.com"
    design:
      columns: '1'
      spacing:
        padding:
          - 50px
          - '0'
          - 50px
          - '0'

---
