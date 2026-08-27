---
layout: people
title: Isha Garg, Varshith Gude & Soham Pradhan
cover: /assets/images/xenium.png
profile:
  align: right
  image: xenium.png
paper_title: Virtual RNA Inference of Xenium spatial transcriptomics from H&E in colorectal cancer
youtube: https://www.youtube.com/embed/2gQGaV_oJfU
poster: xenium.pdf
abstract: Spatial transcriptomics technologies such as 10x Genomics Visium and Xenium enable measurement of gene expression while preserving spatial context within tissue but remain costly and low throughput, limiting routine clinical application. Virtual RNA inference (VRI) offers an alternative by predicting spatial gene expression directly from hematoxylin and eosin (H&E) histology. This is a modality that is inexpensive and already collected as part of standard clinical workflows. Most existing VRI methods operate at the spot level and have not been evaluated at single-cell resolution, limiting both their biological resolution and demonstrated robustness. We developed and evaluated a graph neural network (GNN) framework that predicts single-cell gene expression from H&E histology in colorectal cancer, pretraining a spatial GraphSAGE architecture on Visium spot-level data before fine-tuning on Xenium single-cell data from a 322-gene targeted panel. During Visium pretraining, the spatial GraphSAGE MIL architecture modestly outperformed a non-spatial MLP baseline on held-out patients (mean Spearman correlation 0.291 vs. 0.276). Transferring only the input normalization and prediction head layers from a non-spatial Visium-pretrained checkpoint combined with a skip connection and a differential learning rate improved on a randomly initialized Xenium baseline (mean Pearson correlation 0.1908 vs. 0.1894; mean Spearman correlation 0.1771 vs. 0.1750) under a patient-level held-out validation design, training on four Dartmouth-Hitchcock Medical Center patients and validating on four independent, held-out patients from the same institution. Downstream analysis of the resulting predicted expression profiles across compositions and spatial organization showed strong anatomical and pathway-level biological coherence, despite compressed absolute confidence scores. These findings indicate that single-cell-resolution VRI can support downstream tumor microenvironment characterization, while highlighting that transfer learning across spatial transcriptomics platforms of differing resolution requires care in which model components are transferred.
summary: We built an AI tool that can look at a standard tissue slide from a colorectal cancer biopsy (the kind every hospital already takes) and predict detailed molecular information about the tumor that would normally require expensive, specialized lab testing to obtain. The goal is to make this kind of deep tumor insight, which could help guide treatment decisions, accessible and affordable for cancer patients anywhere, not just at major research hospitals.
excerpt_title: Q&A
---
**Bios:** [Isha Garg](https://ben-m-7.github.io/editai_internship/people/),[Varshith Gude](https://ben-m-7.github.io/editai_internship/people/),[Soham Pradhan](https://ben-m-7.github.io/editai_internship/people/)

**Program Track:** Advanced Research

**GitHub Username:**  

ishagarg2332
*-Isha Garg*

COOLCODERVG
*-Varshith Gude*

SohamPradhan64
*-Soham Pradhan*


**What was your favorite seminar? Why?**  

My favorite seminar was the first one because I think I related to it the most in terms of what I hope to pursue in the future.
*-Isha Garg*

My favorite seminar was Thanosan’s presentation on Bayesian Neural Networks for Spatial Transcriptomics. Since his work closely connected to my own project, I really enjoyed seeing a different approach to a similar problem. It gave me a fresh perspective on my own work and made me think about how different methods can tackle the same challenge.
*-Varshith Gude*

I really enjoyed the presentation by Elijah Renner and Ishan Ramrakhiani talking about their research and entrepreneurship, because it shows that students doing the EDIT program can see success in Y Combinator right out of high school. It's a very interesting success story, and it's very nice to see how their passions for computational biology ultimately helped them build their paths toward technical entrepreneurship.
*-Soham Pradhan*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

I learned a lot, collaborated a lot, and had a lot of fun along the way.
*-Isha Garg*

A summer of learning way more biology than I expected, getting humbled by HPC more times than I’d like to admit, and slowly turning a bunch of confusing and complex ideas into something that actually worked.
*-Varshith Gude*

This summer I built an AI pipeline with my teammates (and now friends) that predicts spatial gene expression directly from routine tissue slides, turning a multi-institutional collaboration between Dartmouth and Cedars-Sinai into a working proof-of-concept that could make molecular-level cancer insights accessible without expensive sequencing.
*-Soham Pradhan*


