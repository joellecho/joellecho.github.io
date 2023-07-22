---
layout: project
title: "Effectiveness of a Novel Diet for Weight Loss in Women"
subtitle: "A Randomized Clinical Trial with Varying Treatment Effects Over Time"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Objective.**
In the autonomous vehicle domain, safety is paramount. Given the unpredictable nature of inclement weather conditions, it is critical to ensure that vision-based models can operate reliably under such challenging scenarios. This project aims to enhance the accuracy of the Unimatch model (as presented in CVPR 2022) for scenarios involving adverse weather.

**Methodology.** <br/>
- **Base Model**: The foundational model for this project is the Unimatch model, a cutting-edge technique introduced at CVPR 2022. This model serves as our starting point and will undergo modifications to better accommodate inclement weather conditions.  

- **Data Source**: Our experiments leverage the "Driving Stereo" dataset, accessible at Driving Stereo Dataset. This dataset offers a diverse set of stereo images captured under various driving and weather conditions, making it an apt choice for our transfer learning objectives.  

- **Approach**: Transfer learning, an effective technique for repurposing pre-trained models for new tasks, is our primary method. We will fine-tune the Unimatch model using stereo images from the Driving Stereo dataset that are representative of inclement weather conditions. This process will help the model generalize better to challenging weather scenarios and thus improve its reliability.<br/>

**Outcomes.** <br/>
{%
	include image_with_caption.html
	url="/assets/projects/2023_transfer-learning-unimatch/main.png"
	width="100%"
%}