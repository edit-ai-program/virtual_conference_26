---
layout: people
title: Anuva Shah
cover: /assets/images/virtual.png
profile:
  align: right
  image: virtual.png
paper_title: A Comparative Analysis of Deep Learning Approaches for Virtual H&E Staining from Autofluorescence Imaging
youtube: https://www.youtube.com/embed/nDc2VcRfVWw
poster: virtual.pdf
abstract: Hematoxylin and eosin (H&E) staining is the most widely used tissue staining practice in pathology. However, H&E staining is destructive and restricts further same-sample assays. In contrast, autofluorescence (AF) imaging is label-free and non-destructive, but lacks the color contrast and nuclear delineation H&E provides. With virtual staining emerging as a promising avenue for translating tissue-imaging modalities, this study evaluated the feasibility of generating biologically accurate virtually stained colon H&E patches from corresponding autofluorescence images. Four architectures were compared- a U-Net trained with supervised regression, a pix2pix conditional generative adversarial network, a CycleGAN trained with adversarial, cycle-consistency, and nuclei-density losses, and a latent diffusion model trained to denoise AF-conditioned latents from a frozen variational autoencoder. Each model was trained for 100 epochs on the same 48,777 colon patch pairs and tested on 16,406 pairs. Architectures were evaluated across two metric categories- pixel-level accuracy and biological fidelity. The Structural Similarity Index (SSIM) and Peak Signal-to-Noise Ratio (PSNR) evaluated pixel accuracy, while biological fidelity was assessed using HoVer-Net for nucleus detection and classification, and UNI2-h, a pathology foundation model, for embedding comparison. The two metric families ranked models inversely. The U-Net achieved the highest SSIM (0.35) and PSNR (15.17 dB) but recovered only 30% of the nuclei present in real H&E and reached a cosine similarity of 0.074, scoring lower than the 0.322 similarity between two unrelated real H&E patches. Conversely, the CycleGAN scored lower on pixel-level metrics (SSIM 0.21, PSNR 14.18 dB) yet matched nucleus counts most closely at a ratio of 0.972. It produced the lowest class-distribution error at 0.119 and was the only architecture to substantially exceed 0.322, reaching 0.504. The latent diffusion model, hypothesized to perform best, performed worst overall, constrained by a frozen autoencoder whose reconstruction alone reached only 0.71 SSIM. Thus, pixel-level and biological accuracy metrics diverge sharply in virtual staining, and SSIM and PSNR alone can favor models that discard diagnostically relevant information. Virtual staining evaluation should therefore incorporate nucleus-level and embedding-based measures alongside image quality metrics.
summary: Doctors diagnosing diseases like cancer from tissue samples typically rely on a chemical dye process called H&E staining, which uses up part of the sample in making it visible under a microscope. My project alleviates this by building AI models capable of instantly generating that H&E image from a non-destructive scan called autofluorescence imaging, allowing for quicker diagnoses and better preserved tissue.
excerpt_title: Q&A
---
**Bios:** [Anuva Shah](https://edit-ai-program.github.io/editai_internship/people/)

**Program Track:** Advanced Research

**GitHub Username:**  

anuvashah
*-Anuva Shah*


**What was your favorite seminar? Why?**  

My favorite seminar was Zarif Azher's presentation on the overlap of entrepreneurship and academic research. Hearing Zarif talk about the similarities between the scholarly and more business-focused approaches to AI cleared up many of my questions about which pathway I want to pursue career-wise. I'd love to hear him come back and share more information and advice!
*-Anuva Shah*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

This summer internship was informative, community-building, and fun!
*-Anuva Shah*


