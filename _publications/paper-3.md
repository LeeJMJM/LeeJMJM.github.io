---
title: "An Intelligent Fault Diagnosis Method"
collection: publications
category: manuscripts
excerpt: 'This paper integrates physical kowledge into deep-learning models for gear fault severity levels classification with better intepretability.'
date: 2025-06-01
venue: 'IEEE Transactions on Industrial Informatics'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10931774/'
citation: '<b>Jiaming Li</b>, Xian-Bo Wang, Hao Chen, Zhi-Xin Yang*. Physical-knowledge-guided and interpretable deep neural networks for gear fault severity level diagnosis. <i>IEEE Transactions on Industrial Informatics</i>. 2025, 21(6): 4892–4903.'
---

While deep-learning (DL) models have achieved significant achievements in fault diagnosis, their inherent opacity for human users often hinders practical applications in risk-sensitive scenarios. Fortunately, the advent of class activation mapping (CAM) significantly enhanced the transparency of DL models by illuminating the specific input areas that contribute more to the classification results. Nevertheless, CAM fails to enhance diagnostic accuracy and actively leverage interpretability due to its passively explanatory property for the trained models. To address this issue, in this article, a physically meaningful regularization (PMR) term is proposed by using gradient-weighted CAM, to guide the models in focusing on the same frequency bands of the input spectra and ignoring other parts of noisy and irrelevant signals. Based on the PMR term, a two-step back propagation training algorithm is accordingly designed to train the diagnostic models embedded with physical knowledge. Consequently, the obtained physical-knowledge-guided and interpretable DL models can offer not only strong interpretability but also a higher diagnostic accuracy for the noised test samples. Finally, the proposed diagnostic method is validated in two datasets containing multiple fault severity levels. The diagnostic results, along with the saliency analysis, substantiate the efficacy of the proposed method.
<br/>
<img src='/images/Method and paper introduction CAM.jpg'>
