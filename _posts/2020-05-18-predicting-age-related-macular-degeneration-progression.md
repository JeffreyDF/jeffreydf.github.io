---
title:  "Predicting conversion to wet age-related macular degeneration using deep learning"
date:   2020-05-18 12:00:00
categories: health amd progression oct
permalink: predicting-amd-progression
---

{% include image.html img="/images/2020_nature_medicine_amd_progression/amd_progression_visualization.gif" title="High level overview of the system used for wet AMD conversion prediction." caption="High level overview of the system used for wet AMD conversion prediction. We have two deep learning based models: one uses the original raw OCT scan to predict conversion, the other uses the segmented version of the raw OCT into several tissue types to predict conversion. Their predictions are ensembled to provide a single prediction of the risk to conversion within 6 months."  url="/images/2020_nature_medicine_amd_progression/amd_progression_visualization.gif" %} 
We look at the predicting the progression of an eye to the sight-threatening form of AMD within 6 months. We demonstrate a deep learning system that is able to outperform five out of six experts on this task and importantly also overcomes the high interobserver variability from the experts.  
[**Nature Medicine article**](https://www.nature.com/articles/s41591-020-0867-7){:target="_blank"}  
[**Open-access link**](https://rdcu.be/b4fgc){:target="_blank"}  
[**DeepMind blog post**](https://deepmind.com/blog/article/Using_ai_to_predict_retinal_disease_progression){:target="_blank"}  

{% include image.html img="/images/2020_nature_medicine_amd_progression/amd_progression_timeline.svg" title="Timeline overview of an example patient's progression to wet AMD together with the model's risk prediction." caption="Timeline overview of an example patient's progression to wet AMD together with the model's risk prediction."  url="/images/2020_nature_medicine_amd_progression/amd_progression_timeline.svg" %} 


_Jason Yim*, Reena Chopra*, Terry Spitz, Jim Winkens, Annette Obika, Christopher Kelly, Harry Askham, Marko Lukic, Josef Huemer, Katrin Fasler, Gabriella Moraes, Clemens Meyer, Marc Wilson, Jonathan Dixon, Cian Hughes, Geraint Rees, Peng T. Khaw, Alan Karthikesalingam, Dominic King, Demis Hassabis, Mustafa Suleyman, Trevor Back, Joseph R. Ledsam\*\*, Pearse A. Keane** &  **Jeffrey De Fauw****_  
<sup>\* equal contribution, order determined randomly <br/>
\** jointly supervised the work</sup>

## Abstract

Progression to exudative ‘wet’ age-related macular degeneration (exAMD) is a major cause of visual deterioration. In patients diagnosed with exAMD in one eye, we introduce an artificial intelligence (AI) system to predict progression to exAMD in the second eye. By combining models based on three-dimensional (3D) optical coherence tomography images and corresponding automatic tissue maps, our system predicts conversion to exAMD within a clinically actionable 6-month time window, achieving a per-volumetric-scan sensitivity of 80% at 55% specificity, and 34% sensitivity at 90% specificity. This level of performance corresponds to true positives in 78% and 41% of individual eyes, and false positives in 56% and 17% of individual eyes at the high sensitivity and high specificity points, respectively. Moreover, we show that automatic tissue segmentation can identify anatomical changes before conversion and high-risk subgroups. This AI system overcomes substantial interobserver variability in expert predictions, performing better than five out of six experts, and demonstrates the potential of using AI to predict disease progression.
