---
layout: people
title: Afya Shaikh
cover: /assets/images/fluid.png
profile:
  align: right
  image: fluid.png
paper_title: Classification of Fluid Cytology Whole-Slide Images Using Pretrained Vision Models and Multiple-Instance Learning
youtube: https://www.youtube.com/embed/vOfQ6-3TDbs
poster: fluid.pdf
abstract: Fluid cytology is an important diagnostic tool for detecting malignant and atypical cells in body fluids, but automated analysis of whole-slide images (WSIs) remains challenging because diagnostically important cells may be sparse and unevenly distributed. Detailed cell-level annotations are also often unavailable. This study evaluated whether pretrained vision models and multiple-instance learning (MIL) could classify fluid cytology WSIs using slide-level diagnoses alone.  The original dataset contained 80 WSIs across four diagnostic categories- negative, atypical, suspicious for malignancy, and positive for malignancy. Four unreadable slides were excluded, leaving 76 analyzable WSIs. Twenty-four candidate 512 × 512-pixel patches were extracted from each slide, and patch quality was assessed using sharpness, contrast, and stained-area measurements. The eight highest-quality patches were retained per slide, producing a final dataset of 608 patches.  Pretrained ResNet-18, DINOv2, and Phikon-v2 models were used to generate image embeddings. Baseline classifiers combined patch-level predictions to produce slide-level diagnoses, while DINOv2 and Phikon-v2 embeddings were also evaluated using attention-based MIL. Performance was measured with five-fold slide-level cross-validation.  The ResNet-18 baseline achieved 35.5% accuracy and a 34.1% macro F1 score. Quality-controlled DINOv2 achieved 38.2% accuracy, and DINOv2 with MIL reached 43.4% accuracy and a 41.9% macro F1 score. An equal-weight DINOv2 and Phikon-v2 MIL ensemble produced the highest exploratory performance, with 46.1% accuracy, 45.5% balanced accuracy, and a 45.2% macro F1 score. Positive-for-malignancy slides showed the strongest class-specific performance, with 70% recall and a 67% F1 score.  Quality-controlled patch selection and MIL improved slide-level performance, but results remained limited by the small dataset, overlap among diagnostic categories, sparse WSI sampling, and absence of cell-level annotations. Larger annotated datasets and independent validation are needed before clinical use.
summary: I developed a computer-based method to analyze digital microscope slides made from fluid cytology samples, where cells collected from fluids such as urine or pleural fluid are examined for signs of cancer. The method showed the most promise for recognizing slides positive for malignancy, while also showing that larger datasets and more detailed cell labeling are needed before this approach could be used in clinical care.
excerpt_title: Q&A
---
**Bios:** [Afya Shaikh](https://edit-ai-program.github.io/editai_internship/people/HS_Afya_Shaikh)

**Program Track:** Advanced Research

**GitHub Username:**  

AfyaS
*-Afya Shaikh*


**What was your favorite seminar? Why?**  

My favorite seminar was Dr. L’s because he introduced me to a completely new topic involving neuropathology, neural networks, and how the brain processes information. I have never been especially interested in neuroscience before, so I found it really interesting how he connected biological neurons and brain function to artificial intelligence and digital pathology. His explanation made the topic feel much more understandable and showed me how neuroscience can connect to computational research in new ways.
*-Afya Shaikh*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

My summer internship was an amazing experience that allowed me to experiment and research computational pathology in new ways, build more research and technical skills, and gain a better understanding of how technology can be applied to real-world medical problems.
*-Afya Shaikh*


