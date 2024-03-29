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
  - Webpack
  - Github
  - Vercel
summary: "A responsive web application that serves as a weightlifting calculator to help me with my health goals."
---

<div class="text-center p-4">
  <img src="../img/calculator/smolovjr.png" class="img-thumbnail" >
</div>

I developed the weightlifting calculator as a web application as part of a personal project, with the primary goal of helping me with my health and fitness.

My website is equipped with two different calculators. The Smolov Jr calculator is designed to assist users in implementing the renowned Smolov Jr program, optimizing their training for increased strength. Additionally, the one-rep max calculator, utilizing the Brzycki formula, offers a reliable method to estimate your maximum lifting capacity.

This weightlifting calculator is a frontend application that utilizes React.js framework for its hooks and reusable components, enabling it to efficiently manage stateful logic. This application also uses Bootstrap 5 for its intuitive grid system and responsive design features to create a sleep and visually appealing user interface.

All of the calculations for my weightlifting website were made using JavaScript, ensuring seamless execution within the browser environment, allowing users to conveniently perform dynamic calculations.

Here is some code that illustrates how my application performs its calculations:

```
  const [maxLift, setMaxLift] = useState(0)
  const [increment, setIncrement] = useState(5)

  const maxChange = (e) =>{ setMaxLift(e.target.value) }

  const incrementChange = (e) =>{ setIncrement(e.target.value) }

  const customRound = (value, step) => { return 2.5 * Math.floor((Math.floor(value) + step / 2) / step); }

  const calculateWeight = (percentage) => {
    const roundedWeight = customRound(maxLift * percentage, 2.5);
    return roundedWeight;
  }
```
In the future, I plan to use Webpack which provides a powerful and flexible solution for managing and optimizing the build process of your application.