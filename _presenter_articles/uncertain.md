---
layout: people
title: Alice Qian
cover: /assets/images/uncertain.png
profile:
  align: right
  image: uncertain.png
paper_title: Reading the Residual- Understanding Uncertainty in Virtual RNA Inference from H&E in Colorectal Cancer
youtube: https://www.youtube.com/embed/Eal1yzNkKwM
poster: uncertain.pdf
abstract: Spatial transcriptomics measures gene expression in situ but remains far less accessible than routine hematoxylin-and-eosin (H&E) histology. Virtual RNA inference (VRI) could extend molecular information to H&E-only tissue archives, but its usefulness depends not only on prediction accuracy, but also on whether the model recognizes when its predictions are unreliable. An uncertainty-aware, single-cell VRI pipeline was developed using paired Xenium and H&E from colorectal cancer. Failure was analyzed through a four-part framework- aleatoric noise, epistemic uncertainty, setup/batch effects, and unexplained residual error. The first two are estimated by the model; the last two require external analysis. The model recovered meaningful cross-patient signal, with mean Spearman correlation ρ = 0.296 across 20 transcriptional programs and a best program of ρ = 0.706. However, prediction accuracy and uncertainty reliability were largely independent across programs (ρ = −0.22). Neutrophil degranulation ranked third in prediction accuracy (ρ = 0.579) but its uncertainty was essentially unrelated to its own errors (ρ = −0.034). The most confident prediction intervals were also overconfident- the best-predicted program covered only 74.5% of true values inside a nominal 95% interval. Split conformal calibration restored near-nominal coverage across all 20 programs. Epistemic uncertainty also failed to increase on a new patient (0.99× the training-patient level), even though patient novelty was detectable from the same frozen UNI features (AUC 0.78 unsupervised; 0.93 supervised). Separately, cross-patient calibration revealed measurable setup/batch effects, while additional residual errors remained outside the model-reported uncertainty. These findings show that understanding when and why VRI models fail is essential, and that predictive accuracy alone is insufficient for evaluating trustworthy VRI.
summary: I am developing an AI system that looks at standard microscope images of colorectal cancer tissue and predicts patterns of gene activity that would normally require expensive molecular testing. The project focuses on understanding when and why the AI makes mistakes, whether it can recognize when it may be wrong, and which errors remain hidden, so future tools like this can be used more safely and reliably.
excerpt_title: Q&A
---
**Bios:** [Alice Qian](https://edit-ai-program.github.io/editai_internship/people/)

**Program Track:** Advanced Research

**GitHub Username:**  

AliceQian2010
*-Alice Qian*


**What was your favorite seminar? Why?**  

A really impactful seminar for me was Dr. Zarella’s AI in Pathology presentation. I found it especially interesting to hear how AI is already being used in pathology, the challenges, and future vision for it. I heard about how models that perform well in one hospital may not generalize to another, and that AI should become more robust and clinically integrated, helping pathologists recognize useful signals and better trust and use the tool.
*-Alice Qian*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

Fun, educational, and inspiring, and I am incredibly lucky to learn from such amazing mentors!
*-Alice Qian*


