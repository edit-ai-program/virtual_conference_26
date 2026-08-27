---
layout: people
title: Ethan Effendi & Aaditya Panchal
cover: /assets/images/cyto.png
profile:
  align: right
  image: cyto.png
paper_title: PanCyto- A ViT Cytology Foundation Model Trained on a Corpus Spanning Diverse  Cell Morphologies
youtube: https://www.youtube.com/embed/S1ENHRzaOvQ
poster: cyto.pdf
abstract: Cytology screening can require examination of millions of cells in a single whole-slide image (WSI). Supervised models must first acquire cell morphology (nuclear-to-cytoplasmic ratio, chromatin texture, nuclear contour) before a clinical task can be learned, and that cost is incurred again for each new model. A cytology foundation model would avoid the repetition by supplying embeddings in which morphology is already encoded. A corpus of single-cell images was constructed from cytology WSIs. An automated pipeline isolates each object at native scanner resolution and masks the background to white, so scanner tint, stain batch, and nearby debris cannot substitute for morphology. The urine arm comprises 2,602,934 classified single cells across four categories; the cervical arm comprises 2,511,848 detected objects across 89 Pap slides. A Vision Transformer (ViT-Small, 12 layers, 22M parameters) was pretrained with DINOv3ona class-balanced62,667-image subset of the urine corpus,andfrozenclass-tokenembeddings were evaluated. A linear probe attains 78.9% balanced accuracy against a 25% chance rate and a 22.3% label-permutation control. The same embedding is not clusterable. Silhouette coefficients lie near zero, and the leading principal component accounts for only 2% of the variance. Variance occupies an effective rank of 234.7 of 384 dimensions, excluding representational collapse, and residual probe errors fall along cytologically coherent axes. A supervised probe with an explicit permutation reference, rather than clusterability, is the appropriate evaluation for this class of model. The pan-specimen claim remains untested pending a second extracted specimen type and a transfer evaluation.
summary: Cytology requires a pathologist to screen thousands to millions of cells in a whole-slide image sample for telling signs of diseases like cancer. People are using deep learning to provide computer-guided assistance, and we're hoping to give other researchers a better starting point by creating a foundation model that represents their single-cell images in a meaningful, numerical form. 
excerpt_title: Q&A
---
**Bios:** [Ethan Effendi](https://ben-m-7.github.io/editai_internship/people/),[Aaditya Panchal](https://ben-m-7.github.io/editai_internship/people/)

**Program Track:** Advanced Research

**GitHub Username:**  

ethaneffendi
*-Ethan Effendi*

aadityapanchal7
*-Aaditya Panchal*


**What was your favorite seminar? Why?**  

I'm having a tough time choosing between two: the one by Dr. Vaickus and the presentation from Elijah Renner and Om Patel. 
Dr. Vaickus's presentation was inspiring to me because it revealed just how important rigor and attention to detail are in medical science. What he discussed was also useful because I ended up inheriting a lot of data for my own project from AutoParis-X. Dr. Vaickus's talk was like a precursor to reading the full paper, taking notes, and trying to understand how to create my corpus. 
I enjoyed the seminar by Elijah and Om because they exposed to us the startup world. Research truly shouldn't live in an academic vacuum. We need people to translate research into startups that turn ideas into products. 
*-Ethan Effendi*

My favorite seminar was by Ishan Ramrakhiani, and Elijah Renner, since they really went into depth about their experiences with Y Combinator. This gave me really good insight into the field of startups and gave me motivation to build something of my own and really contribute for greater good.
*-Aaditya Panchal*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

The EDIT AI program was a) an exhilarating accelerator of my skills in medical AI research through hands-on work and b) a great way to connect with a teammate whom I hope to continue working with in and out of the lab in the future. 
*-Ethan Effendi*

My time within this summer internship was exhilarating, getting to meet a lot of cool people as well as contribute to something that could possibly save countless lives one day.
*-Aaditya Panchal*


