---
layout: people
title: Charles Fry & Krish Pruthi
cover: /assets/images/cellularity.png
profile:
  align: right
  image: cellularity.png
paper_title: Deep Learning–Based Automated Tumor Cellularity Quantification in Triple-Negative Breast Cancer
youtube: https://www.youtube.com/embed/Y3UmcS0UM0k
poster: cellularity.pdf
abstract: Triple-negative breast cancer (TNBC) is an aggressive type of breast cancer, and it is important to know how well a tumor responds to treatment. Tumor cellularity, which is the amount of the tumor bed region that is made up of cancer cells, is one of the main measures pathologists use to check treatment response. However, doing this by hand takes a long time and can vary between different pathologists. Deep learning can help automate this process using whole-slide images (WSIs).  We built a pipeline that uses a DeepLabV3 based model to segment tissue, alpha-shape boundaries to outline tumor regions, and then analyzes the cells inside those regions to measure tumor cellularity in TNBC. For detecting cells, we compared two models, CellViT and HoVer-Net, to see how well each one identified neoplastic and non-neoplastic cells inside the tumor regions. CellViT uses a Vision Transformer designed for nuclei segmentation and classification. HoVer-Net uses a convolutional network that predicts nuclear boundaries, separates nearby nuclei, and classifies cell type all at once.  By using both models in the same pipeline, we were able to test whether the choice of nuclei detection model changes the cellularity results. Neither CellViT and HoVer_Net were reliably accurate at identifying cellularity. HoVer_Net consistently identified a greater amount of nuclei at the cost of processing speed. This work opens the possibility to a more automated and consistent way to study tumor structure and cell composition, and could eventually support artificial assisted evaluation of treatment response in the clinic. 
summary: We tested and compared two AI-based models on their ability to identify the tumor cells in  breast cancer samples. In the future, this can help doctors identify the amount of tumor left after initial treatment to diagnose more if necessary.
excerpt_title: Q&A
---
**Bios:** [Charles Fry](https://edit-ai-program.github.io/editai_internship/people/),[Krish Pruthi](https://edit-ai-program.github.io/editai_internship/people/)

**Program Track:** Advanced Research

**GitHub Username:**  

Purple-Urchin
*-Charles Fry*

KrishP48
*-Krish Pruthi*


**What was your favorite seminar? Why?**  

My favorite seminar was from Pei-Cheng Peng on July 17th. It was fascinating but also frustrating learning about how we can implement LLMs in prescribing treatment. It stuck with me how LLMs overprescribe chemo because it rids the cancer most efffectively, but it misses how hard chemo is on the body and patient's well being, so it's still important to have a human make the final decision
*-Charles Fry*

My favorite seminar was Zarif Azer's. His research on multimodal modeling and combining imaging with data like spatial transcriptomics to improve cancer prognosis predictions was really fascinating and impactful. I also really enjoyed hearing about his entrepreneurship journey and how he started his own company. 
*-Krish Pruthi*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

It was difficult but I really enjoyed learning the tools including Jupyterlab and alphashape, because even though I won't be majoring in pathology, these tools will be useful in many fields, and in the future I can contribute an engineering perspective to the current digital pathology problems.
*-Charles Fry*

A steep but exciting learning curve into computational pathology and deep learning.
*-Krish Pruthi*


