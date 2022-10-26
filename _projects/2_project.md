---
layout: page
title: Deep Learning to Detect COVID-19
description:
img: assets/img/covid_cnn.png
importance: 1
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/covid_cnn2.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Complete System Architecture for COVID-19 Detection with CNN
</div>

Deep Learning has improved multi-fold in recent years and it has been playing a great role
in image classification which also includes medical imaging. Convolutional Neural Networks (CNNs)
have been performing well in detecting many diseases including coronary artery disease, malaria,
Alzheimer’s disease, different dental diseases, and Parkinson’s disease. Like other cases, CNN has a
substantial prospect in detecting COVID-19 patients with medical images like chest X-rays and CTs.
Coronavirus or COVID-19 has been declared a global pandemic by the World Health Organization
(WHO). As of 8 August 2020, the total COVID-19 confirmed cases are 19.18 M and deaths are 0.716 M
worldwide. Detecting Coronavirus positive patients is very important in preventing the spread of
this virus. On this conquest, a CNN model is proposed to detect COVID-19 patients from chest X-ray
images. Two more CNN models with different number of convolution layers and three other models
based on pretrained ResNet50, VGG-16 and VGG-19 are evaluated with comparative analytical
analysis. All six models are trained and validated with Dataset 1 and Dataset 2. Dataset 1 has 201
normal and 201 COVID-19 chest X-rays whereas Dataset 2 is comparatively larger with 659 normal
and 295 COVID-19 chest X-ray images. The proposed model performs with an accuracy of 98.3% and
a precision of 96.72% with Dataset 2. This model gives the Receiver Operating Characteristic (ROC)
curve area of 0.983 and F1-score of 98.3 with Dataset 2. Moreover, this work shows a comparative
analysis of how change in convolutional layers and increase in dataset affect classifying performances.

Please find the relevant <a href="https://github.com/Foysal1565/COVID-19-Detection-AI-MDPI">code repository and dataset here.</a>
