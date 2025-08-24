---
layout: post
title: Detecting improvised explosive devices (IEDs) in waste receptacle using vision transformer (ViT).
description: Hidden improvised explosive devices (IEDs) in dustbins present major hazards to the lives of the populace. This project was intended to develop an advanced AI algorithm to detect explosives within waste bins using Vision Transformers (ViTs). In this work I, gathered quality database of images which includes IEDs and non-IEDs images, identified suitable algorithm of deep learning to detect IEDs in dustbins effectively, fine-tuned pretrained ViT, and trained model for multiple classes of wastes so it can detect IED among these classes. 
Among multiple varaints of ViTs (ViT-Base/16, ViT-Base/32, ViT-Large/16, ViT-Large/32, and Vit-Huge/14), I chose ViT-Base/16 and fine-tuned as follows.
The outcomes make it explicit that; ViTs perform better (86.59% accuracy) in capturing the global information in an image as compared to CNNs.
skills: 
  - Machine learning
  - Computer vision
  - Vision transformers
  - Data augmentation
  - Data pre-processing
  - Fine tuning

main-image: /waste.png
---

---
{% include image-gallery.html images="/ViT_accuracy.png" height="400" %}
**ViT-Base/16 leveraged the concept of transformer based architecture and achieved 86.59% test accuracy.**

