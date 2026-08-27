---
layout: people
title: Vedhsai Thiriveedi
cover: /assets/images/generative.png
profile:
  align: right
  image: generative.png
paper_title: Spatial Transcriptomics-Informed Histopathologic Image Generation for Modeling the Skin Tissue Microenvironment
youtube: https://www.youtube.com/embed/f_7oTfMtxEA
poster: generative.pdf
abstract: Spatial transcriptomics (ST) has transformed the study of tissue biology by coupling genome-wide gene expression with spatial histologic context, but its high cost limits application to large patient cohorts. While considerable effort has focused on predicting molecular measurements from routine histology, comparatively little attention has been devoted to the reverse problem- generating biologically informed histopathologic images directly from spatial transcriptomic measurements. Such models could enable simulation of tissue microenvironments, facilitate mechanistic studies of tissue organization, and augment computational pathology workflows in data-limited settings. Here, we present an initial evaluation of ST-informed histopathologic image generation in human skin using a conditional latent diffusion model conditioned on spatial gene expression, tissue architecture and cell type proportions. Across 39,579 Visium ST spots from sixteen patients, annotated for seven tissue architectures, generated images produced varied, realistic histologic representations that preserved key characteristics of the underlying tissue microenvironment. Quantitative analyses using CellViT[LST1.1] demonstrated significant agreement in cellular abundance between real and generated tissues for epithelial, stromal, and immune cellular composition. We next evaluated whether these generated tissues improve downstream computational pathology tasks– i) ST inference, ii) tissue architecture classification. Although generative augmentation did not produce practically meaningful improvements in overall spatial gene expression prediction (Δ = +0.0103), inference improved most in adnexal (Δ = +0.0175, p = 0.002) and dermal (Δ = +0.0110, p = 0.010) regions, while architecture classification (Δ macro-F1 = +0.0141) improved most for inflammatory (ΔF1 = +0.0376) and stromal (ΔF1 = +0.0360) tissue. These results suggest that generative modeling preferentially benefits specific tissue microenvironments rather than uniformly improving all prediction tasks, providing an initial benchmark for future ST-informed histopathologic image generation work. Future improvements in image realism and representation learning may further expand the utility of ST-informed generative pathology.
summary: Doctors can examine a piece of skin under a microscope, and they can separately run an expensive test that shows which genes are switched on in that same tissue. I built an AI system that works backward from those gene readings to draw what the tissue should look like under the microscope, then measured how closely the drawings matched real tissue and whether they could help train other medical AI tools when real samples are scarce.
excerpt_title: Q&A
---
**Bios:** [Vedhsai Thiriveedi](https://edit-ai-program.github.io/editai_internship/people/HS_VedhSai_Thiriveedi)

**Program Track:** Mentor

**GitHub Username:**  

Vedhsai-codes
*-Vedhsai Thiriveedi*


**What was your favorite seminar? Why?**  

My favorite seminar was the one that taught how to create deliverables such as research papers. This really deepened my understanding of what I've learned so far and will help me in my future work in the program. 
*-Vedhsai Thiriveedi*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

I built a model that generates tissue images from gene data.
*-Vedhsai Thiriveedi*


