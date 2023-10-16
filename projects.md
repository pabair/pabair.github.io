---
layout: projects
title: "Projects"
---
<h3 class="fw-bold border-bottom pb-3 mb-5">Projects</h3>
Here is a collection of projects that my students were working on (usually as part of a project work at the University of Applied Sciences Karlsruhe).

## Waste Classifier 
\[[Demo](http://193.196.37.242:7860/)\]
\[[Source Code](https://github.com/Gabriel9753/Waste-Classification-Project)\]

In this project Ilyesse Hettenbach and Gabriel Schurr developed an machine learning based system that can classify images showing household waste into one of the categories of the German waste system: "Restmüll", "Organic", "Wertstoff", "Papier" und "Glas".

 <img src="{{ site.github.url }}/assets/img/wasteclassify.png" alt="Home" width="80%">

A user can upload a picture showing waste, select between different classification models (EfficientNet-B3, EfficientNet-B4, VGG19, ResNet50 or DinoV2) and get a online estimate about the correct waste category.

To train and finetune the ML models effciently on the German waste system, they enriched existing dataset with self-taken images of household waste and labeled them accordingly.
