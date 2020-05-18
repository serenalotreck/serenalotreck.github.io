---
layout: page
title: "projects"
permalink: projects/
---
![Picture of Heart Lake from the summit of Mount Jo in the Adirondacks](../images/MtJo.JPG)

### Using machine learning interpretability to examine genetic interactions
----------
The model organism *Saccharomyces cerevisiae* provides a perfect study system for genetic interactions. Using a fitness assay, where the relative size of the colony represents the fitness of that genotype, it is simple and high-throughput to characterize the phenotypes of any number of mutants. Using a dataset of single and double mutants, we have developed a machine learning model to predict the fitness of yeast double mutants (DMs). We can then go a step further and define, based on the DM fitness and single mutant (SM) fitness for each gene in the DM pair, what type of genetic interaction we observe: additive (no interaction), worse than additive (synergistic), or better than additive (antagonistic).<br>

Machine learning interpretability techniques will allow us not only to create a near-perfect model to predict double mutant fitness, they will also allow us to “get under the hood” of genetic interactions. What features contribute to the misprediction of DMs? What biological relevance do these features have? By delving into an instance-based, local interpretation of the model, we can examine the mechanisms that result in the three types of observable genetic interactions. 

### Domain-specific knowledge graph reasoning
---------
In 2008, the scientific community published the [50 millionth scientific article](https://onlinelibrary.wiley.com/doi/abs/10.1087/20100308). Now, there are an estimated [2.5 million articles published each year](https://digitalcommons.unl.edu/scholcom/9/). If we could read all the papers in the world, we would likely be able to uncover knowledge that is true, but that we haven’t noticed, and also make predictions about things that may be true, based on what we do know. However, the sheer number of articles is overwhelming. Even if we were to narrow down by a specific sub-discipline, e.g., “flowering time”, a well-studied domain within plant biology, the search yielded 16,053 results. Knowledge Graph Reasoning (KGR) is a computational pipeline involving the application of machine learning over Knowledge Graphs (KGs), to the problem of extracting meaningful information from the plant biology literature. KGs connect entities, which are ideas or things, with edges that represent the relationships between two entities. KGR reads the articles of interest, creates a KG representing the information within the given body of literature, and allows queries of the resulting KG for relevant information. Additionally, we plan to use KGR to explore the presence of conflicting information within the literature, and to predict information that may be truse based on established facts. By using KGs and KGR to uncover conflicts and knowledge gaps, we will be able to explore why those conflicts exist, and resolve scientific questions that until now have remained elusive because we lack a full perspective on published science. 

