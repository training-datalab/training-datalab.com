---
title: Minería de datos servicio civil chileno
date: 2020-01-01
authors: ["bgonzalezbustamante"]
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
Proyecto finalizado financiado por la Universidad de Santiago de Chile y apoyado por Training Data Lab
{{% /callout %}}

Las fuentes originales de información corresponden a datos liberados por la DNSC en respuesta a las solicitudes AE004T0000240 y AE004T0000484 en el marco de la Ley 20.285 sobre Acceso a la Información Pública, realizadas el 26 de diciembre de 2016 y el 26 de abril de 2018, respectivamente. Con la primera solicitud elaboramos una base de datos de altos directivos públicos para el período 2009-2015 (*N* = 391, véase también [González-Bustamante, 2020]({{< relref "../publication/2020-11-18-the-politics-administration-dichotomy" >}})).

<!--more-->

Con esta base de datos y la segunda solicitud elaboramos un listado de 452 directivos del primer nivel jerárquico para el período 2009-2017. Posteriormente, recopilamos 1.396 documentos públicos, entre decretos de nombramiento, actas de los concursos, noticias institucionales, entre otros similares.

Los documentos fueron cargados en la plataforma [Open Science Framework (OSF)](https://doi.org/10.17605/OSF.IO/WBF6M) y se les asignó una URL permanente única que nos permitió aplicar un algoritmo de reconocimiento óptico (OCR) programado específicamente para este propósito. De esta forma, los documentos PDF fueron convertidos en imágenes PNG que fueron cargadas en el repositorio del proyecto en GitHub que está conectado con OSF (*surv-civil-servants*, actualmente privado y pronto disponible para consulta pública).

Las imágenes se convirtieron a un formato de texto manejable a través del proceso previamente descrito con el fin de emparejar y verificar los documentos con los casos identificados. Esto nos permitió validar los casos.

**Recursos**

* [SocArXiv preprint en inglés](https://doi.org/10.31235/osf.io/vshcz).
* [Artículo publicado en español]({{< relref "../publication/2020-12-01-altos-directivos-publicos-un-nuevo-conjunto-de-datos-de-miembros-del-servicio-civil-chileno" >}}).
* [Proyecto OSF](hhttps://doi.org/10.17605/OSF.IO/WBF6M).
* [Repositorio en Zenodo](https://doi.org/10.5281/zenodo.8115596).

**¿Cómo citar esta base de datos?**

* González-Bustamante, B., Astete, M., & Orvenes, B. (2021). Survival of the Senior Civil Servants in the Chilean Executive Branch. Dataset, versión preliminar 1.13.19 -- Bold Lab, bajo acceso restringido. University of Oxford, Universidad de Santiago de Chile (USACH) y Training Data Lab. https://doi.org/10.5281/zenodo.8115596.

_Última actualización: 6 de julio de 2023._