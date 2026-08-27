---
layout: people
title: Avilash Angirekula
cover: /assets/images/agent.png
profile:
  align: right
  image: agent.png
paper_title: A Lab-Personalized AI Agent for Digital Pathology Research
youtube: https://www.youtube.com/embed/1jqMEe7yI8A
poster: agent.pdf
abstract: Research groups accumulate code, notebooks, and configuration across shared computing infrastructure faster than they document it. Once a project ends, recovering the data and analysis behind a result often means reconstructing it, and the reasoning behind a given choice may exist only with whoever performed the work. Commercial AI assistants are the obvious remedy and not an available one- clinical data governance requires institutional review and a Business Associate Agreement before protected data may be transmitted, and cloud endpoints are versioned and retired, which undermines reproducibility over the lifetime of a study. We deployed a 30.5-billion-parameter open-weight language model on Dartmouth's Discovery cluster and built a retrieval-augmented generation pipeline over a laboratory's own files, with no outbound network request at any stage. Researchers reach the system through a Slack interface that dials out from the cluster, a design required because the cluster cannot accept inbound traffic. We evaluated retrieval accuracy against a colleague's cytology project, used with permission and restricted to code, configuration, and notebooks- 49 files indexed as 637 retrievable passages. Thirty questions were written by reading the corpus, each paired with the file containing its answer, including five whose answers were absent from it entirely. The correct source file appeared among the top three results for 92% of answerable questions (23/25), with a median response latency of 14 seconds. The system declined four of the five unanswerable questions and never declined one it could answer. Profiling attributed indexing cost to directory traversal rather than embedding, reducing index construction from 340 seconds to under one. Two of three observed failures shared a single cause in dense-vector retrieval, which yields a specific and testable remedy. Indexing a real corpus also surfaced a practical hazard- file paths and slide manifests carry patient identifiers that content-level filtering does not remove.
summary: When a scientist finishes a project, the knowledge of exactly how they did it often lives only in their head, and the next researcher can lose days working out which piece of code produced which result. We built an assistant that reads a lab's own files and answers those questions in plain English, running entirely on the lab's own computers so that patient information never leaves the building, and it always shows you which files it read.
excerpt_title: Q&A
---
**Bios:** [Avilash Angirekula](https://edit-ai-program.github.io/editai_internship/people/HS_Avilash_Angirekula)

**Program Track:** Advanced Research

**GitHub Username:**  

aviangirekula
*-Avilash Angirekula*


**What was your favorite seminar? Why?**  

The one on NLP for Clinical Text Reports, as well as Y Combinator. I thought it was the most interesting because the topics that were covered seemed very impactful (although not the most related to my project this summer), and I loved hearing about the YC expirence because I believe startups are definitely what I'd want to pursue in the future.
*-Avilash Angirekula*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

I built a research assistant that lets a lab ask questions about its own code and data in plain English, got it running on real hospital research files, and found that the hard part was not making it clever, but making it honest about what it did not know.
*-Avilash Angirekula*


