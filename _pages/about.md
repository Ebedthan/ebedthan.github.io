---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a bioinformatician and biostatistician at the [Institut National Polytechnique
Félix Houphouët-Boigny (INPHB)](https://www.inphb.edu.ci) in Yamoussoukro,
Côte d'Ivoire, where I hold an Assistant Professor position. My work sits at the
intersection of computational biology and statistical modeling. I spend most of my
time thinking about how to extract meaningful biological signal from complex, noisy
data.

My current research focus is on **Bayesian hierarchical modeling** and
**statistical software development**. On the modeling side, I build hierarchical
Bayesian models in [Stan](https://mc-stan.org/) to characterize how microbial
communities are structured across environmental gradients and spatial scales. I am
particularly drawn to problems where data are sparse or heterogeneous, and where
honest uncertainty quantification matters, which describes most real ecological
datasets. My statistical interests extend to prior sensitivity analysis, model
comparison workflows, and the principled translation of biological questions into
generative models.

On the software side, I develop open-source tools primarily in
[Rust](https://www.rust-lang.org/) for performance and reliability, and in [R](https://www.r-project.org/) and
[Python](https://www.python.org/) for statistical and analytical workflows. Tools I develop and maintain include:

- **[`xgt`](https://github.com/ebedthan/xgt)**: efficient querying and parsing of
  GTDB taxonomic data
- **[`hkgfinder`](https://github.com/ebedthan/hkgfinder)**: HMM-based housekeeping
  gene finder for prokaryotic (meta)genomic data
- **[`sabreur`](https://github.com/ebedthan/sabreur)**: fast and reliable
  demultiplexing of FASTX files
- **[`hyperex`](https://github.com/ebedthan/hyperex)**: primer-based extractor for
  16S rRNA and other SSU/LSU hypervariable regions
- **[`cedar`](https://github.com/ebedthan/cedar)**: rapid neighbor-joining tree
  construction from sequences using Mash distance

I enjoy the challenge of building tools that work well in resource-constrained
environments, whether that is a CLI that runs fast on modest hardware, or a model
that gives honest uncertainty estimates on a small field dataset.

## Writing

I am currently writing two open textbooks aimed at life scientists and agronomists:

- [*Modern Analysis of Variance*](https://ebedthan.github.io/maov): a practical guide to ANOVA and its extensions for
  researchers working with experimental and observational data in biology and
  agronomy, with an emphasis on model understanding over mechanical application.
- [*Writing Statistical Models in Stan: A Practical Handbook for Life Scientists*](https://ebedthan.github.io/stan-handbook): a
  hands-on introduction to Bayesian workflow and probabilistic programming in Stan,
  built around worked examples from ecology and field experimentation.

Both books are being developed in [Quarto](https://quarto.org/) and will be made
freely available online.

## Teaching

I teach across the engineering and technology programs at INPHB, covering statistics,
experimental design, and scientific methodology. My current and recent courses
include:

**Statistics and data analysis**
- *Descriptive Statistics*: first-year students, 30 h,
  covering the full data lifecycle from collection and cleaning to graphical
  exploration and summary statistics, with worked examples.
- *Inferential Statistics*: second-year students, 20 h, covering
  hypothesis testing, confidence intervals, and introductory regression.
- *Agricultural Experimentation with Computing Applications*: third year students, 30 h,
  practical design and analysis of field experiments using statistical software.
- *Biometry and Crop Experimentation*: Master students, two tracks (Crop protection engineer and crop production engineer); 20 h each,
  covering experimental design and biometric analysis for agricultural engineers.

**Scientific methodology**
- *Research Methods and Scientific Writing*: Master students; 14 h each,
  covering literature search strategies, critical reading, and scientific writing
  conventions.

**Computing**
- *Spreadsheet Mastery (Excel)*: third year students; 15 h, practical data management and
  analysis in Excel for agricultural technicians.
- *Computer Science*: Classes préparatoires BCPST (first and second year); taught
  from 2022 to 2024, covering programming and computational foundations for students
  entering life science and agronomy engineering programs.

Beyond the classroom, I contribute to the [INPHB Fab Lab](https://www.inphb.ci/),
where I am involved in the design of smart connected greenhouse systems used for
student training in agricultural technology.

## Collaboration

I am open to collaboration on Bayesian modeling, bioinformatics tool development,
amplicon sequencing workflows, or applied biostatistics. Feel free to reach out via
the contact page or at [ediman.ebou@inphb.ci](mailto:ediman.ebou@inphb.ci).
