---
layout: single
permalink: /software/
title: "Software"
excerpt: "Open-source tools for bioinformatics and computational biology"
author_profile: true
---

I develop and maintain open-source command-line tools primarily in
[Rust](https://www.rust-lang.org/) for performance and reliability, and in [R](https://www.r-project.org/) and
[Python](https://www.python.org/) for statistical and analytical workflows. All tools are freely available on
[GitHub](https://github.com/ebedthan).

## Taxonomy and Genomics

**[xgt](https://github.com/ebedthan/xgt)**
&nbsp;·&nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust)

Efficient command-line tool for querying and parsing taxonomic data from the
[Genome Taxonomy Database (GTDB)](https://gtdb.ecogenomic.org/). Supports full
taxonomy lookup, lineage tracing, taxon comparison across releases, and bulk
queries via the GTDB REST API. Designed for speed on large-scale genomic datasets.


**[hkgfinder](https://github.com/ebedthan/hkgfinder)**
&nbsp;·&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

HMM-based tool for identifying and extracting housekeeping genes from prokaryotic
genomes and metagenomes. Built for use in both isolate genomics and
metagenomics-first workflows, where reliable single-copy marker genes are needed
for normalization or phylogenetic anchoring.

**[cedar](https://github.com/ebedthan/cedar)**
&nbsp;·&nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust)

Rapid neighbor-joining phylogenetic tree construction directly from sequences,
using [Mash](https://github.com/marbl/Mash) distance estimation. Designed for
quick exploratory phylogenetics on large sequence sets without requiring a
full alignment step.

## Amplicon Sequencing

**[hyperex](https://github.com/ebedthan/hyperex)**
&nbsp;·&nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust)

Primer-based extractor for hypervariable regions of 16S rRNA and other SSU/LSU
marker genes. Useful for standardizing amplicon datasets across studies that
targeted different variable regions, or for in silico primer evaluation.


**[sabreur](https://github.com/ebedthan/sabreur)**
&nbsp;·&nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust)

Fast and reliable demultiplexing of FASTX files based on barcode sequences.
A modern, maintained alternative to the original
[SABRE](https://github.com/najoshi/sabre), with improved error handling and
performance on large sequencing runs.

## Statistical Modeling

**R packages and modeling frameworks**

I am currently developing R packages implementing Bayesian ecological modeling
frameworks, with a focus on microbial community analysis, prior sensitivity
analysis, and model comparison workflows built around
[Stan](https://mc-stan.org/) and [CmdStanR](https://mc-stan.org/cmdstanr/).
These projects will be made public in the coming months.


*If you use any of these tools in your work, feedback and contributions are
welcome via GitHub. For questions or collaboration inquiries, feel free to
[get in touch](/contact/).*
