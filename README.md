# Thesis Mirja Vink

Student name: Mirja Vink
Student number: 760031

This repository contains the code used in my thesis titled _"High five, down low, too slow: Anticipating haptic greeting with multiscale vision transformers"_. The research involves different variations of one model used on different temporal lengths of the haptic greetings dataset. The model used is called MviTv2. 

**Repository Structure**

Exploratory data analysis: This notebook contains the code that was used for the exploratory data analysis. 

Pre-processing: This folder contains the pre-processing notebook that was used for the trimming of the frames for different temporal lengths. This also contains the augmentation and the random oversampling used on the full videos.  

In the thesis, a couple experiments were conducted. First of all, different temporal framelengths were chosen and trimmed to see the impact on the F1-score. The code for these are available in the folder 'Frames'. The full videos were also used as input for the model and on these full video augmentation and random oversampling techniques were employed. These are all available in the folder 'Full set'. 

_Reference to the specific libraries and github repositories that were used in this code: _

-  Takuya Akiba, Shotaro Sano, Toshihiko Yanase, Takeru Ohta, and Masanori Koyama. 2019. Optuna: A Next-generation Hyperparameter Optimization Framework. In KDD (arXiv).

- Erdem Akca. (2023). ThesisErdemAkca. GitHub. URL: https://github.com/Erdem0900/ThesisErdemAkcahttps://github.com/Erdem0900/ThesisErdemAkca

- Shayana Libhatti (2021)Video Augmentation Code. URL: https://github.com/shayanalibhatti/Video-Augmentation-Code

- Alves, R. (2019). Video Augmentation. GitHub. https://github.com/Rafalves883/Video-Augmentation/blob/master/Code

