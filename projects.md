---
layout: page
title: "Projects"
---
Here is a collection of projects that my students were working on (usually as part of a project work at the University of Applied Sciences Karlsruhe).

## Waste Classifier 
\[[Demo](http://193.196.37.242:7860/)\]
\[[Source Code](https://github.com/Gabriel9753/Waste-Classification-Project)\]
\[[Report](https://pabair.github.io/assets/PA_waste-classification.pdf)\]

In this project Ilyesse Hettenbach and Gabriel Schurr developed an machine learning based system that can classify images of household waste into one of the categories of the German waste system: "Restmüll", "Organic", "Wertstoff", "Papier" und "Glas".

 <img src="{{ site.github.url }}/assets/img/wasteclassify.png" alt="Home" width="80%">

A user can upload a picture, select between different machine learning classification models (EfficientNet-B3, EfficientNet-B4, VGG19, ResNet50 or DinoV2) and get a estimate about the waste category.

To train and finetune the ML models effciently on the German waste system, they enriched existing dataset with self-taken images of household waste and labeled them accordingly (see their [report](https://pabair.github.io/assets/PA_waste-classification.pdf) for details).
