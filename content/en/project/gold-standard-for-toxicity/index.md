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

{{% callout note %}}
Project in progress funded by the Universidad Diego Portales and supported by Training Data Lab
{{% /callout %}}

<!--more-->

**Overview**

This project aims to create and validate a *gold standard* for a set of machine learning algorithms and language models that measure political toxicity and incivility in the digital sphere.

For this purpose, we conducted manual data labelling to validate and evaluate deep learning algorithms and Large Language Models (LLMs) applied to protest events in Latin America and to the digital interactions that occurred during the functioning of the Constitutional Convention in Chile.

The creation of this reference standard will constitute an empirical contribution that will make it possible to assess the relevance and coherence of the results obtained by applying generative transformers and other machine learning techniques. This constitutes a relevant contribution in terms of algorithmic transparency and artificial intelligence in the social sciences.

**Design**

Our empirical strategy uses two unpublished data sets of digital interactions on Twitter (now X). The first contains over 5 million interactions during three protest events in Latin America: (a) protests against the coronavirus and judicial reform measures in Argentina during August 2020; (b) protests against education budget cuts in Brazil in May 2019; and (c) the social outburst in Chile stemming from protests against the underground fare hike in October 2019. The second contains more than 31 million messages and more than 9 million interactions over a two-year period covering the functioning of the Constitutional Convention in Chile (January 2021 to December 2022).

In a first stage, we use different algorithms and models on this data to detect toxicity, insults, threats, among other indicators associated with digital incivility. Among the models we use are Perspective, ToxicBERT, LlaMa2 and 3 and different Generative Pre-Trained Transformers (GPT) such as GPT-3.5-Turbo and GPT-4. Then, we manually labelled a balanced subsample of the digital interactions in the Chilean case (*n* = 2,000) in order to build and validate a reference standard.

**Expected outcomes**

The project's milestones of relevance are two conference presentations (July 2024 in Lisbon and October 2024 in Zurich), a WoS-SSCI article published in a first or second quartile journal according to its impact factor (to be submitted for evaluation in November-December 2024) and a data set available for reuse in other research to be released via GitHub/Zenodo with a DOI (to be released in mid-2025).

**Preliminary results and progress**

* Blog post: [Training Data Lab participates in the XII Latin American Congress of Political Science]({{< relref "../post/2024-07-25-xii-latin-american-congress-of-political-science" >}}).

_Last updated: 25 July 2024._