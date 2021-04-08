---
layout: paper
title: "Scaling computational genomics to millions of individuals with GPUs"
year: "2019"
shortref: "Taylor-Weiner et al. Genome Biology 2019"
nickname: scaling-with-gpus
journal: "Genome Biology"
volume: 20
issue: 1
pages:
authors: "Taylor-Weiner A, Aguet F, Haradhvala NJ, Gosai S, Anand S, Kim J, Ardlie K, Van Allen EM, Getz G"
image: /assets/images/papers/Taylor-Weiner2019_Fig1.png
pdf:
pdfLink: https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1836-7

doi: 10.1186/s13059-019-1836-7
pmid: 31675989
pmcid: PMC6823959
category: paper
published: true
peerreview: true
tags: [genomics, GPU]
---
{% include JB/setup %}

# Abstract

Current genomics methods are designed to handle tens to thousands of samples but will need to scale to millions to match the pace of data and hypothesis generation in biomedical science. Here, we show that high efficiency at low cost can be achieved by leveraging general-purpose libraries for computing using graphics processing units (GPUs), such as PyTorch and TensorFlow. We demonstrate > 200-fold decreases in runtime and ~ 5-10-fold reductions in cost relative to CPUs. We anticipate that the accessibility of these libraries will lead to a widespread adoption of GPUs in computational genomics.