---
layout: people
title: Vivaan Mahajan
cover: /assets/images/rcb.png
profile:
  align: right
  image: rcb.png
paper_title: NLP for RCB Extraction from Breast Cancer Pathology Reports
youtube: https://www.youtube.com/embed/aGEqjhlImto
poster: rcb.pdf
abstract: Background- Residual Cancer Burden (RCB) is a clinically useful measure of response after neoadjuvant therapy for breast cancer, but retrospective calculation requires multiple pathology variables that may be inconsistently documented. We evaluated whether relatively small, locally hosted language models can reliably extract the variables needed for RCB assessment from post-neoadjuvant breast pathology reports.  Methods- We assembled a multicenter corpus of 857 pathology reports and evaluated four local models- Qwen2.5-7B-Instruct, Qwen3.5-9B, Phi-4-mini-instruct, and Maple-preview. A frozen structured extraction schema covered tumor-bed dimensions, overall cancer cellularity, in situ percentage, positive lymph nodes, largest nodal metastasis, reported RCB score/class, and pathologic complete response (pCR). The primary benchmark used an untouched 80-case human-annotated set, of which 59 cases were eligible for field-level scoring. A separate 30-case RCB-enriched stress set tested performance when target variables were more frequently present. A teacher-model analysis of the full cohort estimated real-world variable availability. Downstream RCB reconstruction was additionally evaluated in seven human-reviewed non-pCR cases with sufficient data for formula-based calculation.  Results- Qwen3.5-9B was the strongest extractor. On the untouched benchmark, it achieved 84.7% status-plus-value accuracy, 76.5% presence F1, 69.8% numeric tolerance accuracy, and 87.7% categorical accuracy. On the RCB-enriched stress set, corresponding performance was 82.6%, 85.7%, 77.4%, and 100.0%. Overall cancer cellularity was the most difficult variable, with numeric accuracy of 8.3% on the untouched set and 27.3% on the stress set. Among 650 teacher-eligible reports, the second tumor-bed dimension and cellularity were documented in only 11.8% and 20.3%, respectively, and only 8/650 (1.2%) contained all six conventional RCB calculator inputs. In seven non-pCR formula cases, Qwen3.5 produced calculable outputs in 5/7 and all five matched the human-gold RCB class; other models achieved at most 1/7 correct.  Conclusions- Current-generation local language models can extract clinically meaningful RCB information from free-text pathology reports, but performance varies substantially by model and variable. Automated RCB reconstruction is constrained not only by extraction quality, particularly for cellularity, but also by incomplete source documentation.
summary: We studied whether AI tools that can run securely within a hospital could read breast cancer pathology reports and pull out the information doctors use to measure how much cancer remains after treatment. We found that the best AI model could identify much of this information accurately, but many reports were missing key details altogether, showing that improving medical documentation is just as important as improving the AI.
excerpt_title: Q&A
---
**Bios:** [Vivaan Mahajan](https://ben-m-7.github.io/editai_internship/people/HS_Vivaan_Mahajan)

**Program Track:** Mentor

**GitHub Username:**  

vivaanmahajan14
*-Vivaan Mahajan*


**What was your favorite seminar? Why?**  

My favorite seminar was the one given by Dr. Vaickus on manuscript preparation. I thought this one was special because although the research itself is very important, it is also important that you can write clearly about all your research and prepare a manuscript that is formatted correctly.
*-Vivaan Mahajan*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

I had a very insightful and educational summer where I was able to learn not just more about how to do research through pursuing a project but also how to help others and guide them with their research as I mentored incoming students.
*-Vivaan Mahajan*


