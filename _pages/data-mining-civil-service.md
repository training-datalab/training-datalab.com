---
title: "Training Data Lab - Data Mining Chilean Civil Service"
layout: textlay
excerpt: "Data Mining Chilean Civil Service"
sitemap: false
permalink: /projects/chilean-civil-service
---

# Data Mining Chilean Civil Service

![]({{ site.url }}{{ site.baseurl }}/images/lab-diagrams/civil_service.png){: style="width: 250px; float: right; border: 10px"}

**Researcher:** [Bastián González-Bustamante]({{ site.url }}{{ site.baseurl }}/team/bgonzalezbustamante)

**Assistants:** Matías Astete and Berenice Orvenes

![Project Status: Completed]({{ site.url }}{{ site.baseurl }}/badges/project_status/project_completed.svg) &nbsp;&nbsp; [![English]({{ site.url }}{{ site.baseurl }}/badges/lang/english.svg)](https://training-datalab.com/projects/chilean-civil-service) &nbsp;&nbsp; [![Spanish]({{ site.url }}{{ site.baseurl }}/badges/lang/spanish_inactive.svg)](https://training-datalab.com/projects/chilean-civil-service-spanish)

## Creation of the Dataset

<p align="justify">The sources of information were data released by the DNSC in response to requests AE004T0000240 and AE004T0000484 under Law on Access to Public Information. These requests were made on December 26, 2016, and April 26, 2018, respectively. With the first request, we developed a database of senior public managers for the period 2009-2015 (*N* = 391; see <a href="https://doi.org/10.1111/blar.13044" target="_blank">González-Bustamante, 2020</a>).</p>

<p align="justify">With this database and the second request, we compiled 452 top-level managers for 2009-2017. Subsequently, we compiled 1,396 public documents, including appointment decrees, minutes of contests, institutional news, among other similar documents.</p> <!-- These documents were digitalised with data mining algorithms and reviewed exhaustively with semi-automated procedures.-->

<p align="justify">The documents were uploaded to the <a href="https://doi.org/10.17605/OSF.IO/WBF6M" target="_blank">Open Science Framework (OSF)</a> platform and assigned a unique permalink that allowed us to apply an optical character recognition (OCR) algorithm programmed for this purpose. In this way, the PDF documents were converted to PNG images which were uploaded to the <a href="https://github.com/bgonzalezbustamante" target="_blank">project repository on GitHub</a>, which is connected to OSF (*surv-civil-servants*, currently private and soon available for public consultation).</p>

<p align="justify">The images were then converted to a manageable text format to match and verify the documents with the identified cases. This allowed us to validate the cases.</p>

## Resources

- <a href="https://doi.org/10.31235/osf.io/vshcz" target="_blank">SocArXiv preprint in English</a>.
- <a href="https://doi.org/10.22370/rgp.2020.9.2.2920" target="_blank">Published paper in Spanish</a>.
- <a href="https://doi.org/10.17605/OSF.IO/WBF6M" target="_blank">OSF-Project</a>.
- <a href="https://doi.org/10.5281/zenodo.8115596" target="_blank">Zenodo repository</a>.

### How to cite this dataset?

- González-Bustamante, B., Astete, M., & Orvenes, B. (2021). Survival of the Senior Civil Servants in the Chilean Executive Branch (Version 1.13.19 -- Bold Lab). Dataset, pre-release version under restricted access, University of Oxford, Universidad de Santiago de Chile (USACH) and Training Data Lab. <a href="https://doi.org/10.5281/zenodo.8115596" target="_blank">https://doi.org/10.5281/zenodo.8115596</a>.

<br />
<small>Artwork by DALL·E in an Impressionist style.</small><br />
<small>Diagram by González-Bustamante, Astete and Orvenes (2020).</small><br />
<small>Last updated: July 6, 2023.</small>
