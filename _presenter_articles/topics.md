---
layout: people
title: Maximilian Wakefield
cover: /assets/images/topics.png
profile:
  align: right
  image: topics.png
paper_title: Combining Structured EHR Data and LLM-Extracted Psychosocial Factors from Clinical Notes to Predict Suicide Risk in Cancer Patients
youtube: https://www.youtube.com/embed/5Wf2Yb4KxKE
poster: topics.pdf
abstract: Cancer patients face an elevated risk of suicidal ideation and self-harm, and warning signs are often documented only in free-text clinical notes rather than structured diagnosis codes. Existing suicide-risk prediction models rely primarily on structured electronic health record (EHR) data, and prior natural language processing (NLP) approaches to suicide risk have largely targeted general psychiatric or veteran populations rather than cancer patients specifically. This study developed and validated a large language model (LLM)-based pipeline to extract psychosocial risk factors from clinical notes and evaluated whether this information improves suicide-related risk prediction beyond structured data alone in a cancer cohort from MIMIC-IV (4,614 patients- 769 cases, 3,845 controls). A two-stage LLM pipeline (Qwen2.5-32B) extracted patient-reported, cancer-linked negative psychosocial content from clinical notes, validated against a manually reviewed control set (12 of 12 correct). Extracted evidence was analyzed using Latent Dirichlet Allocation (LDA) topic modeling, which identified six clinically interpretable themes, including a distinct suicidal ideation and depression theme. Logistic Regression, Random Forest, and Gradient Boosting classifiers were trained on structured-only, note-only, and combined feature sets using patient-level, 10-fold cross-validation. Structured-only Gradient Boosting achieved an AUC of 0.792, within the range of published suicide-risk models. Combining structured data with note-derived features significantly improved Random Forest and Gradient Boosting performance (AUC up to 0.827, p<0.001), though not Logistic Regression, indicating that note content adds predictive value specifically for tree-based, nonlinear models. A longitudinal analysis further showed that the rate of psychosocial evidence in notes rose significantly as cases approached their event, while remaining flat in controls (p=0.0053). These findings suggest that LLM-extracted note content provides model-dependent, clinically meaningful predictive value for suicide-related risk in a novel and understudied cancer-specific population.
summary: Cancer patients can show signs of serious emotional distress that get written down by doctors in their medical notes but never show up in the codes and reports hospitals normally use to track patient health. This project built a tool that uses AI to read those notes, pick out signs of genuine emotional distress, and combine that with a patient's medical history to screen for signs of a mental health crisis.
excerpt_title: Q&A
---
**Bios:** [Maximilian Wakefield](https://ben-m-7.github.io/editai_internship/people/)

**Program Track:** Skills Development

**GitHub Username:**  

maximilian229
*-Maximilian Wakefield*


**What was your favorite seminar? Why?**  

My favorite seminar was NLP for Clinical Text Reports & Y Combinator Experience. It connected directly to my own project, since I spent part of the summer applying NLP techniques to extract information from unstructured clinical notes. Hearing about a similar approach applied to clinical text reports felt the most relevant to what I was actually doing, and I learned different approeachs I could use in the future.
*-Maximilian Wakefield*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

The summer internship experience let me explore many different methodologies while getting to work closely with mentors across Dartmouth, whose guidance and feedback helped me develop a significant project.
*-Maximilian Wakefield*


