---
layout: people
title: Ved Dwivedi
cover: /assets/images/nlp.png
profile:
  align: right
  image: nlp.png
paper_title: Open-Weight Large Language Models for Breast Pathology Biomarker Extraction
youtube: https://www.youtube.com/embed/MARtpeEHoe4
poster: nlp.pdf
abstract: Pathology report text contains critical biomarker results; however, these values are part of semi-structured prose and require manual extraction. The performance of five locally hosted open-weight large language models (LLMs) and one regex baseline was evaluated based on their ability to extract 17 fields in a zero-shot setting (no input-output examples). The 17 fields consisted of 12 biomarker value fields for estrogen receptor (ER), progesterone receptor (PR), HER2 immunohistochemistry (IHC), HER2 in situ hybridization (ISH), and Ki-67, as well as five context fields that identified whether each biomarker result referred to the current specimen, a previous specimen, a pending test, was not reported, or was unclear. A held-out test set of 36 pathology reports from The Cancer Genome Atlas (TCGA), as well as an institutional cohort of 100 pathology reports with ground truth created before model evaluation, was used. Metrics included exact field accuracy, core-status accuracy, context accuracy, fully correct reports, strict JSON validity, evidence-span fidelity, runtime, and manual review burden. Qwen2.5-7B-Instruct performed best among the evaluated models, with exact field accuracy of 86.1% and core-status accuracy of 91.0% on the TCGA test set, and 96.5%, 94.2%, 97.0%, and 63.0% for exact field accuracy, core-status accuracy, context accuracy, and fully correct reports, respectively, on the institutional cohort. Falcon3-7B-Instruct showed comparable exact field accuracy on the institutional cohort (95.2%) but lower core-status accuracy (89.2%). Strict JSON validity did not track extraction accuracy- only 7% of Qwen and 1% of Falcon outputs were valid JSON exactly as returned, although the formatting errors were recoverable using predefined rules. Qwen also showed the highest verbatim evidence-span fidelity (94.9%) and the lowest median runtime per case (3.12 seconds). The main remaining source of error was HER2 ISH, especially when reports contained generic FISH language or did not contain a patient-specific ISH result. An exploratory review policy flagged 54% of Qwen reports and captured 86.4% of reports with a core-status error, corresponding to a potential 46% reduction in full-case review. Overall, these results suggest that locally hosted open-weight LLMs can accurately extract breast pathology biomarkers for research purposes, although output formatting, biomarker context, and HER2 ISH results still require careful review.
summary: I researched whether local AI models could analyze breast cancer pathology reports and correctly extract meaningful findings from the reports, such as the results of hormone receptors and HER2 testing, without transmitting patients' confidential information to other organizations. The most accurate model was highly accurate but not error-free, making errors in complex pathology reports, indicating that the use of AI could speed up the review of records by researchers, but humans would still be accountable for validation.
excerpt_title: Q&A
---
**Bios:** [Ved Dwivedi](https://edit-ai-program.github.io/editai_internship/people/)

**Program Track:** Advanced Research

**GitHub Username:**  

vwdr
*-Ved Dwivedi*


**What was your favorite seminar? Why?**  

Among all the great seminars, my favorite one was Dr. Ryan Landvater's seminar on digital pathology and neural networks. The things that attracted me the most were the connections that he made between biological neuron processing and CNNs. It is remarkable how simple local features can be used to create a representation through layering. Another very intriguing thing that Dr. Landvater explained was the difference between segmentation and classification. Namely, a CNN is able to locate nuclei, cells, blood vessels, etc., and after that, determine what they are. The usage of transformers after that step is also clear, as the transformer can take into account the relationship between different features, for example, the correlation between blood vessel wall thickness/distribution and neuropathy's relation to diabetes.
*-Ved Dwivedi*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

A summer full of learning, collaborating, problem solving, and seeing an idea turn into a real project I was proud to present! 
*-Ved Dwivedi*


