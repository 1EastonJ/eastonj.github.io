---
title: Sleep Safety and Health Monitoring (ongoing, and highly likely that a paper will be published)

---

**Jun. 2024 - Present**  
**Advisor:** Prof. Rong Zheng (Computing and Software, McMaster University)
<!--more-->
- Some wearable devices can monitor sleep quality. We aim to replace wearable devices with radar and machine learning methods 
for sleep quality monitoring. This involves using radar to measure key data from the human body, building a model that takes radar data as input, and outputting sleep stages to reflect the user's sleep status.
- Contribute to process heart rate, respiration, and acceleration data, extract features as inputs for a decision tree, and design a rule-based decision tree capable of distinguishing sleep stages.In specific, We aim to use features related to heart rate (HR), respiration rate (RR), and acceleration (ACC) as inputs to predict three sleep stages (Wake, REM, NREM). My responsibility is to address scenarios with missing data. For example, how to determine sleep stages if only HR and RR are available, but ACC is missing.  
  From online datasets, I found one dataset containing HR, RR, and sleep stage (denoted as D1) and another with HR, ACC, and sleep stage (denoted as D2). Initially, I attempted using Random Forest ensemble learning, training separate decision trees on each dataset and combining their results. However, the final accuracy barely approached but still fell short of 70%, showing poor performance.  
  Later, I referred to the article titled *[Development and validation of an algorithm for the study of sleep using a biometric shirt in young healthy adults](#)* and adapted its rule-based decision tree approach. After modifications, the final prediction accuracy improved to 75%.

[More details in this PPT](/uploads/Bedside_Safety_and_Sleep_Monitoring_presentation.pptx.zip)
