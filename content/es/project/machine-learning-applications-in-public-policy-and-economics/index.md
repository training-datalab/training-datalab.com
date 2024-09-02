---
title: Aplicaciones de machine learning en políticas públicas y economía
date: 2021-04-10
authors: ["ccisternas", "Francisco Castañeda"]
image:
  ## caption: 
  focal_point: 'smart'
pager: true
commentable: true
show_related: false
show_breadcrumb: true
draft: false
tags:
- research-project
- completed-project
---

{{% callout note %}}
Proyecto finalizado financiado por la Universidad Mayor y apoyado por Training Data Lab
{{% /callout %}}

Este proyecto aborda la complejidad de distintos fenómenos políticos, sociales y económicos desde un enfoque multidisciplinar a través del análisis de grandes volúmenes de datos. Este proyecto, en particular, busca utilizar y desarrollar aplicaciones de aprendizaje automático para detectar anomalías en datos que utilizan tomadores de decisiones y comprender las dinámicas sociales de consumo de información actuales. En general, este proyecto tiene como objetivo estudiar diversos temas de investigación en ciencias sociales utilizando algoritmos entrenados.

<!--more-->

Un ejemplo ilustrador es Cambridge Analytica, empresa acusada de manipular las elecciones de Estados Unidos en 2016 mediante el posicionamiento de ideas y percepciones en Facebook. En efecto, durante la campaña electoral, la empresa recolectó sin autorización datos de usuarios de esta red social para, posteriormente, realizar campañas micro dirigidas con noticias falsas y desinformación. Este emblemático caso demuestra cómo la manipulación de grandes volúmenes de datos y técnicas de aprendizaje automático permiten afectar resultados políticos y, en consecuencia, impactar en la economía y las políticas públicas de países y regiones completas.

En la primera versión de este proyecto (2do semestre, 2021) nos enfocaremos precisamente en la desinformación sobre temas económicos y de políticas públicas. Para esto, nuestro equipo de investigación ha programado códigos que permiten la descarga de grandes volúmenes de información de prensa y redes sociales digitales en Chile, con el fin de realizar un benchmarking con distintos algoritmos ya entrenados para identificar dinámicas de desinformación sobre ciertos tópicos específicos. De esta forma, pretendemos explorar y evaluar brechas temáticas y comparar su alcance con fuentes de información más tradicionales y confiables.

Un elemento distintivo de este proyecto es que entrenaremos nuestro propio algoritmo con datos de Chile para identificar las dinámicas particulares de la realidad nacional. En este proceso, los estudiantes que se integren a nuestro equipo desempeñarán un rol fundamental mediante el proceso de codificación y etiquetado de submuestras de datos para entregar insumos que permitan entrenar un algoritmo clasificador.

**Objetivos**

Este proyecto busca conformar un equipo multidisciplinario de investigación verticalmente integrado para realizar diferentes aplicaciones de aprendizaje automático en políticas públicas y economía. En esta primera versión, nos centraremos en las dinámicas de desinformación en temas económicos y de interés público. Esperamos abordar y analizar otros fenómenos relacionados con la formulación de políticas públicas sectoriales y regulación de mercados en futuras versiones.

En consecuencia, nuestro objetivo principal para nuestro primer caso de estudio es:

* Entrenar un algoritmo clasificador para identificar niveles de desinformación en temas de políticas públicas y economía en la esfera digital chilena.

La integración vertical con estudiantes nos permite establecer los siguientes objetivos secundarios relacionados con el entorno de tutoría que conformaremos:

* Entrenar a los estudiantes en tópicos básicos de investigación en ciencias sociales.
* Introducir a los estudiantes en temas de aprendizaje automático.
* Capacitar a los estudiantes en fundamentos básicos de programación en R.

**Metodología de investigación**

La integración vertical se realizará entre los estudiantes de distintos años que se integren al proyecto, investigadores responsables y asociados en un entorno de tutoría sincrónico (talleres o reuniones de evaluación de una hora cronológica) y trabajo autónomo semanal asincrónico con datos (tres horas semanales).

Talleres y reuniones semanales sincrónicas:

* Introducción y presentación del proyecto.
* Nociones fundamentales de aprendizaje automático.
* Desinformación y opinión pública.
* Elementos fundamentales de metodología.
* Codificación y etiquetado de datos.
* Fundamentos de R.
* Estadística descriptiva en R.
* Evaluación codificación de datos.
* Modelos lineales en R.
* Modelos logísticos en R.
* Evaluación codificación de datos.
* Regularización y validación cruzada.
* Árboles de decisión y Random Forest.
* Evaluación codificación de datos.
* Presentación y comentarios de análisis preliminares.
* Cierre y autoevaluación de esta primera versión.

Este proyecto se desarrolla desde la Escuela de Negocios de la Universidad Mayor, pero se realizará completamente online. No son necesarios conocimientos previos en estadística o programación, solo se requiere acceso a un computador y conexión a Internet. La evaluación de los estudiantes se realizará durante las reuniones de avance de la codificación de datos (25% cada una) y durante la sesión final a través de una autoevaluación (25 %).

Las tutorías sincrónicas, por una parte, tienen por objetivo capacitar a los estudiantes en temas básicos de investigación en ciencias sociales e introducirlos en temas de aprendizaje automático y programación en R. Por su parte, el trabajo autónomo asincrónico tiene relación con la codificación y etiquetado de información para entrenar nuestro propio algoritmo, lo que será evaluado constantemente en diversas sesiones sincrónicas programadas.

La compilación y etiquetado de los conjuntos de datos se realizarán con códigos programados en R y Python y en plataformas digitales elaboradas por el grupo de investigación al que pertenecen varios miembros de este proyecto que agrupa investigadores de diversas universidades.

**Codificación y aprendizaje automático**

Extraemos dos submuestras considerando algunos mensajes por día de los datos de las redes sociales del referéndum chileno para una nueva Constitución en octubre de 2020 (*N* = 2.529.134). En estas submuestras realizaremos dos procedimientos de codificación de datos para identificar la posición, emocionalidad y credibilidad de la información. Luego, entrenaremos modelos y predeciremos los datos no codificados de las redes sociales utilizando técnicas de aprendizaje automático e incorporando la validación humana en el flujo de trabajo.

Es importante señalar que tanto el conjunto de datos completo como las submuestras han sido debidamente anonimizados con un algoritmo criptográfico basado en una función hash para cumplir con las consideraciones éticas actuales sobre la investigación en medios sociales.

**Propiedad intelectual**

Con el objetivo de fomentar la innovación, la propiedad intelectual de lo creado en este proyecto VIP será compartida entre estudiantes e investigadores responsables y asociados. En consecuencia, los miembros del equipo podrán utilizar los datos levantados para publicaciones propias, agradeciendo y mencionando adecuadamente al proyecto. Esperamos, en futuras versiones, incentivar a los estudiantes más experimentados a utilizar los datos para sumarse a coautorías con investigadores del equipo y que asuman roles de liderazgo para orientar y capacitar a nuevos integrantes.

_Última actualización: 3 de diciembre de 2021._
