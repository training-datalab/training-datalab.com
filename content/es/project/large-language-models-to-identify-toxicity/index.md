---
title: Large Language Models (LLMs) to Identify Toxicity in the Digital Sphere during Protest Events in Latin America
date: 2024-05-04
authors: ["bgonzalezbustamante"]
image:
  ## caption: 'Créditos de la imagen: [**OpenAI**](https://openai.com/)'
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
Proyecto en curso financiado por OpenAI y apoyado por Training Data Lab
{{% /callout %}}

**Resumen**

Este proyecto consiste en una evaluación comparativa y una auditoría de algoritmos de una serie de grandes modelos lingüísticos (LLMs por sus siglas en inglés) para medir la toxicidad y la incivilidad en los medios sociales digitales durante protestas masivas en países latinoamericanos. Desde hace más de una década, la literatura ha reconocido el potencial de los medios sociales digitales y de Internet, en un sentido más amplio, para mejorar la coordinación de la acción colectiva, lo que implica la reducción de los costos de movilización en el contexto de la política contenciosa. Sin embargo, también se ha observado un aumento de la incivilidad y la toxicidad en las interacciones digitales, una situación que puede estar relacionada con comportamientos que erosionan el debate público, como el discurso del odio, las amenazas y el acoso virtual. En este contexto, el uso de LLM y modelos de aprendizaje profundo ofrece la oportunidad de procesar contenidos políticos que manualmente llevarían mucho tiempo. Sin embargo, estos modelos pueden tener sesgos subyacentes derivados de su proceso de entrenamiento que pueden influir en los resultados. En consecuencia, la evaluación comparativa y la auditoría de diferentes modelos nos permite medir su rendimiento para detectar la toxicidad digital y explorar posibles sesgos.

**Diseño**

Utilizamos Perspective API, ToxicBERT, LlaMA 2 y diferentes versiones de transformadores generativos preentrenados (GPT por sus siglas en inglés), como GPT-3.5-Turbo y GPT-4. Aplicamos estos modelos a datos de tres eventos de protesta latinoamericanos: (a) las protestas contra el coronavirus y las medidas de reforma judicial en Argentina durante agosto de 2020; (b) las protestas contra los recortes presupuestarios en educación en Brasil en mayo de 2019; y (c) el estallido social en Chile derivado de las protestas contra la subida de la tarifa del metro en octubre de 2019. Para ello, analizamos más de cinco millones de mensajes publicados en Twitter (ahora X) durante estos eventos de protesta en tres países.

**Resultados esperados**

Nuestros resultados proporcionarán una comparación relevante del rendimiento de diferentes modelos y demostrarán el potencial de la inteligencia artificial generativa para automatizar el etiquetado de contenidos políticos. Además, este trabajo abrirá nuevas posibilidades de investigación para afinar el fenómeno de la toxicidad y el incivismo en las redes sociales digitales o para estudiar las dinámicas digitales durante los actos de protesta en los casos utilizados o en otros contextos similares.

**Resultados preliminares y avances**

* González-Bustamante, B. (2023). [Digital Activism, Protests and Incivility in Latin America](https://doi.org/10.17605/OSF.IO/Q4G6P). Proyecto de investigación, University of Oxford, Universidad de Santiago de Chile (USACH) y Training Data Lab.
* Entrada del blog: [Training Data Lab participa en el XII Congreso Latinoamericano de Ciencia Política]({{< relref "../post/2024-07-25-xii-latin-american-congress-of-political-science" >}}).

_Última actualización: 25 de julio de 2024._