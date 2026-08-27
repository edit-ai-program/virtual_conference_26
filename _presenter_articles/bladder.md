---
layout: people
title: Ameya Rajeev, Abhinav Kakkera, Aqib Nawaz Shaik, Gagan Girish, David Ahn & Joycelyn Cheng
cover: /assets/images/bladder.png
profile:
  align: right
  image: bladder.png
paper_title: Automated Bladder Cancer Screening with Deep Learning Algorithms
youtube: https://www.youtube.com/embed/dgtbu97JKsY
poster: bladder.pdf
abstract: Bladder cancer has one of the highest recurrence rates of any cancer, requiring lifelong monitoring and screening. Distinguishing between benign, atypical, and malignant cells is difficult due to overlapping cell morphology. While the nuclear-to-cytoplasmic (N/C) ratio is an important indicator used in screening, manual evaluation is extremely laborious. This study presents a U-Net-based deep-learning model that segments urothelial cells to calculate their N/C ratios used for diagnosis. We compared the deep learning approach with traditional methods and evaluated its predictive value of the N/C ratio through comparison with patient diagnostic categories to determine its potential for automated screening. Exactly 200 urothelial cell images with ground-truth masks were used to train and validate both methods. For the Otsu baseline, images were converted to grayscale, Gaussian-smoothed, and inverted so nuclei had higher intensity values. Three-class Multi-Otsu thresholding assigned pixels to backgrounds, cytoplasm, and the nucleus followed by morphological filling of small holes. For U-Net, images were resized to 256 x 256 pixels and normalized. U-Net was trained to segment background, cytoplasm, and nucleus using equally weighted cross-entropy and Dice losses. The evaluation dataset consisted of 100 cell images labeled into four categories- positive, negative, atypical, and suspicious. Segmentation performance was evaluated using Spearman’s correlation coefficient (SCC), and a box plot represented how well each method diagnosed the test set into four categories. U-Net achieved a SCC of 0.84, while Otsu’s performed at an SCC of 0.76. Similarly, U-Net produced a box plot closer to the ground-truth plot, than Otsu’s did. These results are statistically significant, and indicate that U-Net was able to diagnose and segment urothelial cell images with greater accuracy than Otsu’s method. This was expected, as Otsu’s is a traditional method, while U-Net is a recent architecture stated to perform well in segmentation tasks. 
summary: We compared the performance of two different methods of how each would model would segment cell images and diagnose it into positive, negative, suspicious, and atypical cells. We found that a newer deep learning method, U-net expectedly performed better than the traditional deep learning method.  
excerpt_title: Q&A
---
**Bios:** [Ameya Rajeev](https://edit-ai-program.github.io/editai_internship/people/),[Abhinav Kakkera](https://edit-ai-program.github.io/editai_internship/people/),[Aqib Nawaz Shaik](https://edit-ai-program.github.io/editai_internship/people/),[Gagan Girish](https://edit-ai-program.github.io/editai_internship/people/),[David Ahn](https://edit-ai-program.github.io/editai_internship/people/),[Joycelyn Cheng](https://edit-ai-program.github.io/editai_internship/people/)

**Program Track:** Skills Development

**GitHub Username:**  

ameyar880
*-Ameya Rajeev*

abhikakkera
*-Abhinav Kakkera*

aqibshaik-dev
*-Aqib Nawaz Shaik*

gagan_g
*-Gagan Girish*

dahn1863
*-David Ahn*

JoyCheng3
*-Joycelyn Cheng*


**What was your favorite seminar? Why?**  

My favorite seminar was the one on clinical perspective of digital and computational pathology by Mark Zarella. I really enjoyed this seminar because I was able to gain a much better understanding of the impact technology can have on pathology, and how it can be used in the real world.
*-Ameya Rajeev*

My favorite seminar was the last seminar. I liked this seminar because it talked about presenting our groups work, and it helped me better present our findings that we concluded. I think this seminar was the most important to me, because I have a fear of presenting, and 
*-Abhinav Kakkera*

My favorite seminar was the one done by Elijah Renner and Ishan Ramrakhiani because I was very interested in their startup work, as well as Elijah's work with medical encoders. I also liked the last seminar where we learned essential writing scores for formal research.
*-Aqib Nawaz Shaik*

My favorite seminar was the last seminar because it helped me learn about the difference between a discussion and the results section. Also taught me on how to present engagingly.
*-Gagan Girish*

My favorite seminar was Manuscript Preparation by Lou because I enjoyed the way he presented and how he conveyed the information. It was a very memorable experience to me and it has stuck with me ever since.
*-David Ahn*

I really liked the seminar about the PREDICT model for breast cancer. I thought it was interesting how it can predict breast cancer outcomes, and it was inspiring to see how widely the model is used by both clinicians and patients. It was also interesting to see how large language models, such as ChatGPT, was able to follow the clinical guidelines very well.
*-Joycelyn Cheng*


**If you were to summarize your summer internship experience in one sentence, what would it be?**  

This summer, I gained experience applying AI and deep learning to real-world medical data while developing a potential approach to improve bladder cancer screening.
*-Ameya Rajeev*

This summer internship was enlightening, it taught me how to collaborate with peers from different timezones, different backgrounds, and different interests. 
*-Abhinav Kakkera*

My summer internship was very fun and informative, I was able to strengthen my machine learning skills while also being able to work with an excellent group of people! 
*-Aqib Nawaz Shaik*

My summer was filled with lots of fun working with my team and learning new things along the way. It taught me how to communicate with others who were different ages, had different backgrounds, and were in different time zones.
*-Gagan Girish*

A major learning experience and an opportunity to collaborate with others from differing backgrounds, interests, and parts of the world.
*-David Ahn*

I thought my summer internship experience was fun and insightful, I was able to collaborate and meet with high schoolers across the country and was able to learn a lot from my project and the seminars.
*-Joycelyn Cheng*


