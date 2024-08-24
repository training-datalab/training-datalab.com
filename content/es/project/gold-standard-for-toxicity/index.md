---
title: Validación de un estándar de referencia para medir toxicidad e incivilidad política en la esfera digital
date: 2024-05-17
authors: ["bgonzalezbustamante", "srivera"]
image:
  ## caption: 'Créditos de la imagen: [**X**](https://)'
  focal_point: 'smart'
pager: true
commentable: true
show_related: false
show_breadcrumb: true
draft: false
tags:
- research-project
- active-project
---

<!--more-->

{{% callout note %}}
Proyecto en curso financiado por la Universidad Diego Portales y apoyado por Training Data Lab
{{% /callout %}}

**Resumen**

Este proyecto tiene por objetivo crear y validar un estándar de referencia (*gold standard*) para un conjunto de algoritmos de aprendizaje automático y modelos de lenguaje que miden toxicidad e incivilidad política en la esfera digital.

Para esto realizamos un etiquetado manual de datos para validar y evaluar algoritmos de aprendizaje profundo y modelos de lenguaje (*Large Language Models*, LLMs) aplicados a eventos de protesta en América Latina y a las interacciones digitales ocurridas durante el funcionamiento de la Convención Constitucional en Chile.

La creación de este estándar de referencia constituirá un aporte empírico que permitirá evaluar la pertinencia y coherencia de los resultados obtenidos aplicando transformadores generativos y otras técnicas de aprendizaje automático. Esto constituye un aporte relevante en términos de transparencia algorítmica e inteligencia artificial en ciencias sociales.

**Diseño**

Nuestra estrategia empírica utiliza dos conjuntos de datos inéditos de interacciones digitales en Twitter (ahora X). El primero contiene más de 5 millones de interacciones durante tres eventos de protesta en América Latina: (a) protestas contra las medidas del coronavirus y la reforma judicial en Argentina durante agosto de 2020; (b) protestas contra los recortes presupuestarios en materia de educación en Brasil en mayo de 2019; y (c) el estallido social en Chile derivado de las protestas contra el alza de la tarifa del metro en octubre de 2019. El segundo contiene más de 31 millones de mensajes y más de 9 millones de interacciones durante un período de dos años que contempla el funcionamiento de la Convención Constitucional en Chile (enero de 2021 a diciembre de 2022).

En una primera etapa, utilizamos distintos algoritmos y modelos en estos datos para detectar toxicidad, insultos, amenazas, entre otros indicadores asociados a incivilidad digital. Entre los modelos que utilizamos se encuentran Perspective, ToxicBERT, LlaMa2 y 3 y diferentes transformadores generativos preentrenados (*Generative Pre-Trained Transformers*, GPT) como GPT-3.5-Turbo y GPT-4. Luego, etiquetamos manualmente una submuestra balanceada de las interacciones digitales en el caso chileno (*n* = 2.000) con el objetivo de construir y validar un estándar de referencia.

**Resultados esperados**

Las metas de relevancia de este proyecto son dos presentaciones en congresos (julio de 2024 en Lisboa y octubre de 2024 en Zurich), un artículo WoS-SSCI publicado en una revista del primer o segundo cuartil según su factor de impacto (será enviado a evaluación en noviembre-diciembre de 2024) y una base de datos disponible para ser reutilizada en otras investigaciones que será liberada a través de GitHub/Zenodo con un DOI (será liberada a mediados de 2025).

**Resultados preliminares y avances**

* Entrada del blog: [Training Data Lab participa en el XII Congreso Latinoamericano de Ciencia Política]({{< relref "../post/2024-07-25-xii-latin-american-congress-of-political-science" >}}).

_Última actualización: 25 de julio de 2024._