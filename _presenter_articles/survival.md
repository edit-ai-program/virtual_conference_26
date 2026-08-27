---
layout: people
title: Diya Ramakrishnan & Shreyas Pendem
cover: /assets/images/survival.png
profile:
  align: right
  image: survival.png
paper_title: Virtual RNA Inference for Survival Prediction in Kidney Renal Clear Cell Carcinoma
youtube: https://www.youtube.com/embed/n-IUe9UFmjY
poster: survival.pdf
abstract: 	Accurate survival prediction for kidney renal clear cell carcinoma (KIRC) remains a critical challenge in clinical oncology. While spatial transcriptomics (ST) can capture molecular features of the tumor microenvironment that are known to be linked with survival prediction for KIRC, it requires expensive wet-lab infrastructure that is unavailable for most archival tissue slides. Virtual RNA Inference (VRI), which involves the prediction of spatial gene expression from routine hematoxylin and eosin (H&E) stained whole slide images (WSI) through the use of AI models, could be a more scalable alternative. In this study, a VRI-based graph neural network (GNN) pipeline was compared against a morphological baseline using UNI patch embeddings for KIRC disease specific survival (DSS) prediction. Both pipelines use identical node-masked SAGEConv graph autoencoder architectures and attention multi-layer perceptron (MLP) survival heads. Both pipelines were trained on 451 TCGA KIRC FFPE patients using 5-fold grouped cross validation and on a held-out test set of 61 patients. The VRI pipeline achieved an ensemble test c-index of 0.623 compared to 0.543 for the baseline, even though the baseline had a higher c-index on fold 3. Spatial attention maps concentrated along tumor-stroma boundaries, which was consistent with known survival-related tissue regions in KIRC. These results show that inferred ST from routine H&E slides can be used to predict survival related outcomes in KIRC but, while it outperformed the morphological baseline, it may not always result in an advantage over a WSI feature extractor. The results of this study suggest the ability of potential large-scale survival prediction from archival pathology collections through these pipelines.
summary: Currently, how long patients' have to live from kidney cancer is predicted by looking at tissue samples under a microscope, but this can miss important molecular details hidden in the tumor. In this project, we developed an AI system that reads these tissue slides and can predict a patient's survival odds by inferring genetic activity of the tumor, potentially allowing for survival prediction for kidney cancer using only routine slides already collected at diagnosis. 
excerpt_title: Q&A
---
**Bios:** [Diya Ramakrishnan](https://ben-m-7.github.io/editai_internship/people/),[Shreyas Pendem](https://ben-m-7.github.io/editai_internship/people/HS_Shreyas_Pendem)

**Program Track:** Advanced Research

**GitHub Username:**  

DiyaRamakrishnan
*-Diya Ramakrishnan*

shreyas4472
*-Shreyas Pendem*


**What was your favorite seminar? Why?**  

My favorite seminar was the Spatial Transcriptomics and Image Generation seminar. I really enjoyed this seminar because it combined two areas of research that I've been currently working in. The seminar especially was valuable because the presenters gave a lot of helpful advice from their own research experiences in this field that my teammate and I were able to apply to our project this summer!
*-Diya Ramakrishnan*

My favorite seminar was the Bayesian VRI because it offers a clear way for the model to convey uncertainty.
*-Shreyas Pendem*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

A contrast of serious scientific experimentation and giggling with new-found friends over mistakes!
*-Diya Ramakrishnan*

EDIT AI allowed me to explore computational biology from a new perspective through mentorship and compute access. 
*-Shreyas Pendem*


