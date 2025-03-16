---
title: 'TextClass Benchmark: Evaluación de LLMs y transformadores para la clasificación de textos en ciencias sociales'
date: '2025-03-16'
authors: ["bgonzalezbustamante"]
image:
  caption: 'Créditos de la imagen: [**TextClass Benchmark**](https://textclass-benchmark.com/)'
  focal_point: 'smart'
pager: true
commentable: true
show_related: false
show_breadcrumb: true
draft: false
tags:
- blog
---

En noviembre de 2024, empecé a trabajar en el proyecto [TextClass Benchmark](https://textclass-benchmark.com/), una iniciativa de evaluación comparativa dinámica y continua diseñada para evaluar Large Language Models (LLMs) y transformadores para tareas de clasificación de textos. El hecho de que el proyecto se centre en las ciencias sociales es significativo, ya que aborda la creciente necesidad de herramientas eficaces de clasificación de textos en este campo. La cobertura actual incluye dominios como la incivilidad digital, la clasificación de agendas políticas y una clasificación incipiente sobre desinformación. El proyecto ha probado 98 modelos, entre ellos los recientes GPT-4.5-preview, DeepSeek-R1 y Gemma 3, casi 3.500 veces.

<!--more-->

El proyecto presenta tablas de clasificación con métricas de rendimiento y clasificaciones relativas mediante un sistema de clasificación Elo adaptado, que se actualiza con cada ciclo para incluir nuevos modelos y datos de prueba no vistos para evaluar el poder de generalización. La idea principal del proyecto no es solo hacer hincapié en la prueba continua de los LLMs, destacando su rendimiento variable en diferentes idiomas y tareas, sino también abordar las limitaciones que han surgido de la combinación de los rápidos avances en IA y aprendizaje automático con los lentos procesos tradicionales de revisión de pares. Este enfoque garantiza que el proyecto siga siendo relevante y tenga repercusión ante los rápidos cambios tecnológicos. Los materiales y las actualizaciones en tiempo real de las clasificaciones Elo están disponibles en [GitHub](https://github.com/bgonzalezbustamante/TextClass-Benchmark) y en la interfaz web del proyecto en [textclass-benchmark.com](https://textclass-benchmark.com/). 

El sistema de clasificación Elo evalúa modelos mediante comparaciones por pares, mientras que la clasificación Meta-Elo combina puntuaciones de dominios específicos para una evaluación exhaustiva. Utilizando un conjunto de datos equilibrado, la tarea del primer ciclo consistió en la clasificación de toxicidad en chino, inglés, alemán y ruso. En este [documento de trabajo](https://doi.org/10.48550/arXiv.2412.00539) se ofrecen más detalles. También ofrece un indicador Meta-Elo que combina y pondera las puntuaciones específicas de cada dominio, teniendo en cuenta la complejidad de la tarea, la escasez de datos lingüísticos y el rendimiento absoluto. Este indicador proporciona una comprensión más matizada del rendimiento de los modelos en diferentes tareas de clasificación, lo que lo convierte en una valiosa herramienta para investigadores y profesionales de las ciencias sociales.

En resumen, el proyecto [TextClass Benchmark](https://textclass-benchmark.com/) es una contribución interesante porque proporciona una evaluación dinámica y justa de LLMs y transformadores para tareas de clasificación de textos en varios dominios comunes de las ciencias sociales y en diferentes idiomas. Este proceso continuo de evaluación comparativa es relevante para comprender el rendimiento de estos modelos en diferentes contextos, especialmente en las ciencias sociales, donde la rápida evolución de las tecnologías de aprendizaje automático e IA puede dejar obsoletos los métodos de evaluación tradicionales. Al ofrecer un sistema completo de evaluación comparativa, este proyecto desempeña un papel crucial para mantener a los investigadores y profesionales al día de los últimos avances, garantizando que utilicen las herramientas más eficaces para sus tareas específicas. El uso de un sistema de clasificación Elo adaptado y la introducción de Meta-Elo añaden solidez y generalización a la evaluación, convirtiéndola en un valioso recurso para la investigación en curso y la aplicación en procesamiento de lenguaje natural y los enfoques de texto como datos.