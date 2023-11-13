---
layout: page
title: "projects"
permalink: projects/
---
![Picture of Heart Lake from the summit of Mount Jo in the Adirondacks](../images/MtJo.JPG)

## Applications of automated information extraction in the plant sciences
My dissertation research focuses on the application of automated information extraction to plant science problems, seeking to simplify and streamline the process of information propagation among scientists to advance scientific progress. A high-level overview is described [here](../pdfs/ComSciCon_2023_article.pdf). More specifically, this work can be broken down into three projects.

------------------
### In a PICKLE: Building out training resources for natural language processing in the plant sciences

Many state-of-the-art algorithms for information extraction tasks require high-quality labeled data in the target domain, in which entities like genes and proteins, as well as the relationships between entities are labeled according to a set of annotation guidelines. While there exist guidelines and datasets for other domains, these resources need development in the plant sciences. In this project, we develop the Plant ScIenCe KnowLedgE Graph (PICKLE) corpus, and provide our annotation guidelines along with an initial corpus of 250 annotated abstracts. Additionally, we perform an analysis of the impact of adding new types to the evaluation of
<br><br>
This work has been [accepted to *in silico* Plants](https://academic.oup.com/insilicoplants/advance-article-abstract/doi/10.1093/insilicoplants/diad021/7413143?utm_source=advanceaccess)! The dataset is available on [Zenodo](https://zenodo.org/records/10076664) and [Huggingface](https://huggingface.co/datasets/slotreck/pickle)

### Examining best practices for automated hypothesis generation in the plant sciences

Annotation efforts for the PICKLE projects demonstrated that our annotation schema was unable to capture the full nuance of information present in published articles. In this project, we leverage several existing datasets and modeling frameworks to examine the impact of annotation schema, dataset topic, and model training procedures on the performance of downstream hypothesis generation.

### Bridging disciplinary gaps in desiccation tolerance research
Using a citation network, we have demonstrated that while desiccation tolerance is a biological phenomenon that exists across kingdoms of life, reseaarchers studying those kingdoms very rarely cite literature from other study systems. This means there is likely untapped information from across disciplines that could be used to generate better hypotheses about the mechanisms of desiccation tolerance in individual systems. In this project, we seek to use the hypothesis generation approaches refined the the previous project to connect reserach areas and generate hypotheses about desiccation tolerance in plants.
<br><br>
Updated: 13 November 2023


