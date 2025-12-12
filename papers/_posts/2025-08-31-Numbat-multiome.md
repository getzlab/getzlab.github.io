---
layout: paper
title: "Numbat-multiome: inferring copy number variations by combining RNA and chromatin accessibility information from single-cell data."
year: "2025"
journal: Briefings in Bioinformatics
authors: Li R, Alberge JB, Keshavarzian T, Tsuji J, Gustafsson J, Rahmat M, Lightbody ED, Deng SL, Riviero S, Miller M, Naz Cemre Kalayci F, Wiestner A, Sun C, Lupien M, Ghobrial I, Parry E, Gao T, Getz G
first_authors: Li R
senior_authors: Getz G
corresponding_authors: Getz G
fulltext: https://academic.oup.com/bib/article/26/5/bbaf516/8290422?login=false
doi: 10.1093/bib/bbaf516
pmid: 41104806
category: paper
---

# Abstract

Aberrant alterations in genome copy number, chromatin accessibility, and transcriptional programs all play pivotal roles in cancer. The Numbat algorithm has been widely adopted to perform copy number variation (CNV) inference from single-cell RNA sequencing (scRNA-seq) data. Here, we introduce Numbat-multiome that extends the capabilities of Numbat to perform CNV inference from both scRNA-seq and accessible chromatin profiles (through single-cell Assay of Transposase [Tn5]-Accessible Chromatin sequencing [scATAC-seq] data), either separately or in an integrated manner. Our approach unifies data originating from different modalities through a binning strategy that relies on a common genomic coordinate system across modalities. We demonstrate the tool's robust performance in four running modes (RNA gene, RNA bin, ATAC bin, and Combined bin) using benchmark cohorts of tumors with dynamic changes in expression patterns and copy number heterogeneity, including early-stage multiple myeloma and Richter's syndrome arising from chronic lymphocytic leukemia, validated against whole-genome sequencing. Numbat-multiome achieves high precision and recall (median F1>0.9) across different CNV event types, with consistent performance across sample types and event lengths. The tool's ability to track clonal evolution in serial samples and identify rare subclones allows for integration of epigenomic profiles at the subclonal level, providing new insights into the stepwise genetic and epigenetic changes underlying cancer phenotypic shifts.