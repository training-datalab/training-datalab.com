---
title: Large Language Models (LLMs) to Identify Toxicity in the Digital Sphere during Protest Events in Latin America
date: 2024-05-04
authors: ["bgonzalezbustamante"]
image:
  ## caption: 'Picture credits: [**OpenAI**](https://openai.com/)'
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
Project in progress funded by OpenAI and supported by Training Data Lab
{{% /callout %}}

**Overview**

This project involves a benchmarking and algorithm audit of a number of Large Language Models (LLMs) to measure toxicity and incivility in digital social media during mass protests in Latin American countries. For more thana decade now, the literature has recognised the potential of digital social media and the Internet, in a broader sense, to improve the coordination of collective action, which implies reducing the costs of mobilisation in thecontext of contentious politics. However, an increase in incivility and toxicity in digital interactions has also been observed, a situation that may be linked to behaviours that erode public debate, such as hate speech, threats and virtual harassment. In this context, the use of LLMs and deep learning models offers an opportunity to process political content that would manually take a long time. However, these models may have underlying biases from their training process that can influence the results. Consequently, benchmarking and auditing different modelsallows us to measure their performance to detect digital toxicity and explore potential biases.

**Design**

We use Perspective API, ToxicBERT, LlaMA 2 and different versions of generative pre-trained transformers (GPT),such as GPT-3.5-Turbo and GPT-4. We apply these models to data from three Latin American protest events: (a) protests against the coronavirus and judicial reform measures in Argentina during August 2020; (b) protests against education budget cuts in Brazil in May 2019; and (c) the social outburst in Chile stemming from protests against the underground fare hike in October 2019. In doing so, we analysed over five million messages posted on Twitter (now X) during these protest events in three countries.

**Expected outcomes**

Our results shall provide a relevant comparison of the performance of different models and demonstrate the potential of generative artificial intelligence to automate the labelling of political content. In addition, this work shallopen new research possibilities for fine-tuning the phenomenon of toxicity and incivility in digital social networks or for studying the digital dynamics during protest events in the cases used or in other similar contexts.

**Preliminary results and progress**

* González-Bustamante, B. (2023). [Digital Activism, Protests and Incivility in Latin America](https://doi.org/10.17605/OSF.IO/Q4G6P). Research project, University of Oxford, Universidad de Santiago de Chile (USACH) and Training Data Lab.
* Blog post: [Training Data Lab participates in the XII Latin American Congress of Political Science]({{< relref "../post/2024-07-25-xii-latin-american-congress-of-political-science" >}}).

_Last updated: 25 July 2024._