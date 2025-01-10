---
layout: paper
title: "Deeper evaluation of a single-cell foundation model"
year: "2024"
journal: Nat Mach Intell
authors: Boiarsky R, Singh NM, Buendia A, Amina AP, Getz G, Sontag D
first_authors: Boiarsky R
senior_authors: Getz G, Sontag D
corresponding_authors: Getz G, Sontag D
fulltext: https://www.nature.com/articles/s42256-024-00949-w
doi: https://doi.org/10.1038/s42256-024-00949-w
pmid: 
category: paper
---

# Abstract

Large-scale foundation models, which are pre-trained on massive, unlabelled datasets and subsequently fine-tuned on specific tasks, have recently achieved unparalleled success on a wide array of applications, including in healthcare and biology1,2,3,4,5,6. The success of these models has showcased the power of leveraging generalizable features and contextual understanding to improve a model’s performance. Single-cell bidirectional encoder representations from transformers (scBERT) by Yang et al.7 is one of several recently developed foundation models to learn representations of single-cell RNA-sequencing data8,9,10,11,12. Yang et al. pre-trained their model on 1.12 million cells to impute masked gene-expression values and characterize the performance of their model on a fine-tuning task to annotate cell types. We reproduce their results, and provide additional baselines and ablation studies (that is, remove components of the model’s architecture or training process) to develop a deeper understanding of their results and the potential benefits and limitations of single-cell foundation models.

(1) We demonstrate that a simple logistic regression baseline outperforms or performs comparably to scBERT on the fine-tuning task of cell-type annotation in two different datasets. This finding holds even in the ‘few-shot learning’ setting, in which the model has access to only a limited number of labelled examples. In the few-shot setting, we would expect scBERT to have an advantage as it uses representations learned via pre-training on massive amounts of unlabelled data never seen by the logistic regression model; however, this is not the case.

(2) We perform ablations on the scBERT architecture and training strategy that shed light on limits to its representation learning capabilities. We show that removing pre-training does not meaningfully affect the model’s downstream performance on cell-type annotation. Furthermore, we show that scBERT can perform well at the masked pre-training task without learning meaningful gene representations.





