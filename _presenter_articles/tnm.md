---
layout: people
title: Shrey Shah, Shreyas Kalidindi & Daniel Gabriel
cover: /assets/images/tnm.png
profile:
  align: right
  image: tnm.png
paper_title: NLP in Pathology Reports
youtube: https://www.youtube.com/embed/kOvVyarJvM4
poster: tnm.pdf
abstract: Pathology reports contain diagnostic and staging information that could be useful for cancer research; however, the majority of information contained in these reports is in complicated clinical text format. It would take a long time to extract this information manually, and regular structured datasets would overlook information contained in pathology reports. NLP can provide an opportunity to automatically identify information related to cancer in these pathology reports. This paper examines NLP techniques to correctly extract cancer-related information in complicated clinical texts by analyzing 9,523 TCGA pathology reports of 32 different cancer types. In our analysis, two tasks are classifying the cancer type and predicting the T, N, and M components of the TNM stage. The traditional machine learning algorithms based on TF-IDF text representations are first tested using Logistic Regression, LinearSVC, Multinomial Naive Bayes, and XGBoost. Using a stratified split for classification of these texts, LinearSVC had a macro-F1 score of 0.967 and an accuracy of 0.975, which were the best among the other classifiers. Secondly, transformer-based language models like BioClinicalBERT are considered for the same set of reports. Although the proposed models had similar performance to the conventional approach in the cancer-type prediction task, long-context transformers like Clinical-ModernBERT showed considerable improvement in the TNM staging task, as much of the staging information is deep within the report and goes beyond the constrained context window available in normal models. Lastly, zero-shot and few-shot prompt techniques were used to evaluate large language models, and they lagged behind other techniques. Therefore, from the findings, it can be noted that the most appropriate technique depends on the task.
summary: Every cancer diagnosis comes with a detailed reports containing critical details, but the information is locked in dense medical language and not feasible to use at scale. Our team taught computers to read these reports automatically, pulling the important details like cancer type.
excerpt_title: Q&A
---
**Bios:** [Shrey Shah](https://edit-ai-program.github.io/editai_internship/people/),[Shreyas Kalidindi](https://edit-ai-program.github.io/editai_internship/people/),[Daniel Gabriel](https://edit-ai-program.github.io/editai_internship/people/)

**Program Track:** Skills Development

**GitHub Username:**  

ShreyShah1000
*-Shrey Shah*

ShreyasK-git
*-Shreyas Kalidindi*

daniel-j-gabriel
*-Daniel Gabriel*


**What was your favorite seminar? Why?**  

My favorite seminar was Dr. Zarella's presentation because he clearly showed the potential of current technology in clinical settings. This seminar really helped me understand the problems ran into with AI in clinical practices as well, and overall it got me very excited to work on future projects!
*-Shrey Shah*

This was my favorite seminar because I found the connection between aging and cancer really interesting. I liked learning how senescent cells can contribute to a tumor-promoting environment and how AI can be used to identify them. I also thought it was interesting that the research could lead to new ways of preventing cancer instead of only treating it after it develops. The examples of AI being used with tissue samples made the connection to technology even more interesting to me. 
*-Shreyas Kalidindi*

My favorite seminar was Zarif Azher's talk on research and entrepreneurship. He drew a really clear line between the work we do at EDIT AI and the way entrepreneurs think and do on a day-to-day basis, and it got me looking at the skills I picked up this summer as something I could carry into my own ventures down the road.
*-Daniel Gabriel*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

Loads of learning, fascinating seminars, and a lot of fun.
*-Shrey Shah*

My summer internship was a hands-on experience where I worked on cancer research using NLP and AI while learning how to approach real research problems and collaborate with a team.
*-Shreyas Kalidindi*


Using coding and AI to contribute to real clinical research while learning the skills needed to do it
*-Daniel Gabriel*


