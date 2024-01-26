---
layout: project
type: project
image: img/calculator/lifte.png
title: "Weightlifting Calculator"
date: 2023
published: true
labels:
  - React
  - JavaScript
  - Bootstrap 5
  - Github
summary: "A responsive web application that serves as a weightlifting calculator to help me with my health goals."
---

<div class="text-center p-4">
  <img src="../img/calculator/smolovjr.png" class="img-thumbnail" >
</div>



byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC

```