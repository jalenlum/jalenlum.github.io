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


I developed the weightlifting calculator as a web application as part of a personal project, with the primary goal of healing me with my health and fitness.

My website is equipped with two different calculaotrs. The Smolov Jr calculator is designed to assist users in implementing the renowned Smolov Jr program, optimizing their training for increased strength. Additionally, the one-rep max calculator, utilizing the Brzycki formula, offers a reliable method to estimate your maximum lifting capacity.

This weightlifting calculator is a frontend application that utilizes React.js framework for its hooks and reusable components, enabling it to efficiently manage stateful logic. This application also uses Bootstrap 5 for its intuitive grid system and responsive design features to create a sleep and visually appealing user interface.

All of the calculations for my weightlifting website were made using JavaScript, ensuring seamless execution within the browser environment, allowing users to conveniently perform dynamic calculations.

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC

```