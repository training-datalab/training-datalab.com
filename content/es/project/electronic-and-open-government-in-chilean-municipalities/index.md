---
title: Patrones territoriales de gobierno electrónico y abierto en los municipios chilenos
date: 2022-08-22
authors: ["bgonzalezbustamante", "daguilar"]
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
- standby-project
---

{{% callout warning %}}
Proyecto en pausa financiado por la Universidad de Santiago de Chile y apoyado por Training Data Lab
{{% /callout %}}

Este proyecto analiza el desarrollo del gobierno electrónico y abierto en los 345 municipios chilenos entre 2019 y 2021. La pregunta principal de este proyecto de investigación es: ¿Qué factores determinan el desarrollo del gobierno electrónico y abierto en las municipalidades chilenas? Para responder esta pregunta elaboramos un índice que combina elementos de gobierno electrónico con indicadores de transparencia para todos los municipios de Chile.

<!--more-->

Para esto utilizaremos el modelo de e-servicios de Esteves (2005) que contiene diversos ítems agrupados en cinco dimensiones para evaluar los sitios gubernamentale (Fath-Allah et al., 2017). Realizamos mediciones de la calidad del gobierno electrónico municipal en las 345 municipalidades de Chile con el fin de obtener un índice agregado de gobierno electrónico (EGi) al cual incorporamos indicadores de transparencia y acceso a la información pública para crear un índice de gobierno electrónico y abierto (EOGi). Este índice compuesto nos permite evaluar el suministro de servicios digitales, el desarrollo del gobierno electrónico y la respuesta a las solicitudes por ley de transparencia a escala municipal.

**Diseño**

Nuestra estrategia metodológica se sustenta en análisis econométrico geoespacial en dos etapas. Primero, describimos y georreferenciamos nuestro índice estimando el nivel de autocorrelación espacial. Luego, ajustamos diferentes modelos econométricos para medir el impacto de la infraestructura tecnológica, nivel socioeconómico y capacidad administrativa en el desarrollo del gobierno electrónico y abierto de los municipios.

**Resultados esperados**

Este proyecto presenta un novedoso conjunto de datos integrados con información geoespacial e indicadores de los gobiernos locales de Chile entre 2010 y 2022. Aplicamos un modelo de servicios electrónicos a los 345 municipios de Chile para medir un índice de gobierno electrónico. Luego ampliamos el índice incorporando indicadores de transparencia a partir de las solicitudes de acceso a la información pública presentadas ante el Consejo para la Transparencia en Chile.

Integramos estas mediciones con información geoespacial e indicadores de gobierno local compilados utilizando los siguientes datos abiertos e información pública:

* Shapefiles geoespaciales y datos del portal Infraestructura de Datos Geoespaciales de Chile y de la Subsecretaría de Desarrollo Regional (IDE-Chile y SUBDERE, 2018, 2020).
* Datos del número de conexiones fijas a Internet a nivel de comunas de la Subsecretaría de Telecomunicaciones (SUBTEL, 2022).
* La tasa de pobreza monetaria de la División de Observatorio Social del Ministerio de Desarrollo Social y Familia y la Comisión Económica para América Latina y el Caribe de la ONU (DOS-MDSF y CEPAL, 2021).
* Indicadores de presupuesto municipal con corrección monetaria y de profesionalización del personal municipal a partir de la proporción que posee título profesional, en ambos casos utilizando datos del Sistema Nacional de Información Municipal de la SUBDERE (SINIM, 2022).
* Población estimada del distrito municipal por el Instituto Nacional de Estadísticas (INE, 2022).

**Recursos**

* [Preprint en SocArXiv](https://doi.org/10.31235/osf.io/gt8a5).
* [Proyecto en OSF](https://doi.org/10.17605/OSF.IO/32WSK).
* [Repositorio en GitHub](https://github.com/bgonzalezbustamante/local-gov-indicators).
* [Repositorio en Zenodo](https://doi.org/10.5281/zenodo.7568387).
* Entrada del blog: [Patrones territoriales de gobierno electrónico abierto. El camino hacia la democracia digital en las municipalidades chilenas]({{< relref "../post/2022-11-01-territorial-patterns-of-open-e-government/" >}}).

**¿Cómo citar este conjunto de datos?**

* González-Bustamante, B., & Aguilar, D. (2023). [Data Set on Local Government Indicators in Chile]({{< relref "../publication/2023-03-17-data-set-on-local-government-indicators-in-chile" >}}). Dataset, versión preliminar 0.21.15 -- Late Sky, University of Oxford, Universidad de Santiago de Chile (USACH) y Training Data Lab.

_Última actualización: 19 de marzo de 2023._