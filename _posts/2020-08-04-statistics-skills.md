---
title: 'A deeper understanding of statistics and inference underlying bioinformatic tools'
date: 2020-08-04
permalink: /posts/2020/08/biostatistics-skills/
tags:
  - statistics

---

### Coordinator: George Savva

Bioinformatics pipelines improves the speed, accessibility, standardisation and computational reproducibility of data analysis.  Yet the inferences that come from them rely on statistical methods that make assumptions that may not be met.  BBSRC and other medical research funders have highlighted potentially inappropriate statistical analysis as a major contributor to irreproducible science.  BBSRC report highlights that ‘pouring more data into conventional research pipelines will compound the problem of non-reproducible findings’ creating a ‘tsunami of data and a blizzard of non-reproducible research findings’.  Improving statistical thinking among users is an important way to avoid research waste.

Statisticians and others working with smaller datasets are used to building diagnostics into their workflows to test assumptions, hence the validity of their inferences. Yet these are difficult to implement in the context of bioinformatics where potentially thousands of hypotheses are simultaneously tested with complex data, and common packages that aim to make analysis easy for beginners do not readily expose the diagnostic or advanced modelling elements of their constituent tools to users, and these may be skipped in introductory courses.  This can have catastrophic consequences for inference.

We will create material for new bioinformaticians emphasising the importance of knowing the assumptions on which inferential tools they are based, how to check that these are met, theoretically and empirically, and how to evaluate claims made by package authors with discussions of how to proceed when they are questionable.
For example, the near ubiquitous use of Benjamini-Hochberg corrections to p-values for multiplicity.  It is our experience that very few scientists can correctly interpret the resulting ‘false discovery rate’, can set appropriate threshold for this or understand the implications of the assumption that individual statistical tests are independent of each other, which is rarely met in practice.

### Methodology
Development of vignettes from real word data.  For each scenario, students will encounter published real world data.  Different tools will be discussed, and their underlying statistical models compared.  Students will consider whether the assumptions are met, how choices in analysis might affect inferences, and how to assess and report their confidence in their findings.
