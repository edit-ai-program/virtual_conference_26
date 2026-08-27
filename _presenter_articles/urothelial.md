---
layout: people
title: Siddhartha Vatsa & Joshua Wang
cover: /assets/images/urothelial.png
profile:
  align: right
  image: urothelial.png
paper_title: Automated Bladder Cancer Screening with Deep Learning Algorithms
youtube: https://www.youtube.com/embed/cn2gtmMzgd4
poster: urothelial.pdf
abstract: Bladder cancer is the 9th most common cancer globally, with non-muscle invasive bladder cancer having 10-year recurrence rates of around 70%. Given these concerning statistics, we combined deep learning and machine learning to build a pipeline that automates and optimizes the urine cytology process. Using a U-Net, we segmented urothelial cells into nucleus, cytoplasm, and background regions, then extracted 5 morphological features (nucleus area, cytoplasm area, N/C ratio, solidity, circularity) to classify the cells into diagnostic reporting categories with a Support Vector Machine. We used traditional multi-Otsu thresholding as a benchmark for segmentation accuracy evaluation. The U-Net achieved a segmentation accuracy of 0.92 on a held out validation split (20% of the 191-image training set) and a mean IOU score of 0.846. The multi-Otsu thresholding produced a mean IOU of 0.662 and a pixel wise segmentation accuracy of 0.91, although only 32% of nucleus pixels were properly detected by the baseline (recall = 0.32). Downstream, the SVM achieved a classification accuracy of 0.68 on a test dataset of 100 images. It performed better than the baseline, which yielded a classification accuracy of only 0.5. Upon analysis of each feature, we found that the most important metric was the nucleus area, not the N/C ratio as we had expected. The second most important feature was the cytoplasm area, which had a Spearman correlation of -0.434. N/C ratio ranked 3rd in the list (from most to least important)- nucleus area, cytoplasm area, N/C ratio, solidity, circularity. Moderate-to-strong positive Spearman correlations of 0.595 between nucleus area and actual category and 0.592 between N/C ratio and actual category indicate that both biomarkers are reliable predictors of malignancy. In conclusion, we found that combining deep learning segmentation with machine learning classification is a more accurate, scalable alternative to traditional computer vision algorithms for automated urine cytology. 
summary: As a common and highly recurrent cancer, bladder cancer requires enhanced screening methods to promote early detection. By combining both deep learning and machine learning algorithms, we were able to better assess abnormalities in cell samples, speeding up the efficiency and accuracy of screening.
excerpt_title: Q&A
---
**Bios:** [Siddhartha Vatsa](https://ben-m-7.github.io/editai_internship/people/),[Joshua Wang](https://ben-m-7.github.io/editai_internship/people/)

**Program Track:** Skills Development

**GitHub Username:**  

svat44
*-Siddhartha Vatsa*

sjedi77
*-Joshua Wang*


**What was your favorite seminar? Why?**  

My favorite seminar was the one with Elijah Renner regarding AI in Entrepreneurship because it aligned with my vision on how we can use AI and machine learning to come up with new innovations.
*-Siddhartha Vatsa*

My favorite seminar was Elijah Renner's seminar on NLP and Y Combinator. I particularly enjoyed it because I have interest in entrepreneurship and liked hearing about his experience with starting a company.
*-Joshua Wang*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

Although I faced a lot of unlucky-timing situations that caused me to be unable to attend a lot of seminars, I definitely learned a lot about cancer pathology and machine learning, and the mentors and Dr. Levy were great and always ready to help.
*-Siddhartha Vatsa*

Amazing learning experience that allowed me to gain insight into the research process and apply machine learning to an impactful project.
*-Joshua Wang*


