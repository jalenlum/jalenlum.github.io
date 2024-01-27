---
layout: project
type: project
image: img/rose/rose.png
title: "Team Robotics and Space Exploration (RoSE)"
date: 2023
published: true
labels:
  - React
  - JavaScript
  - GitHub
  - Jira
summary: "A vertically integrated project(VIP) at the University of Hawai'i at Manoa that strives to design and build a rover that participates in the University Rover Challenge."
---

<div class="text-center p-4">
  <img src="../img/rose/roseui.png" class="img-thumbnail" >
</div>

The Robotics and Space Explorations team, a vertically integrated project (VIP) at the University of Hawai'i at Manoa, is dedicated to designing and building a rover for participation in the University Rover Challenge (URC). Specifically, I am a member of the Ground Station software sub-team, responsible for designing and developing a functional user interface.

To enhance user experience and efficiency, our sub-team has successfully restructured the rover’s control user interface. Our tasks are closely aligned with the progress of other sub-teams within ROSE, and our efforts contribute to the overall success of the project.

This website is built using React, leveraging its hooks and dependencies. This implementation allows for efficient management of stateful logic and enables us to extend React's capabilities. Additionally, it contributes to improved code organization and enhances the overall development experience by providing solutions to common challenges encountered in building modern web applications.

Here is some code that shows the styling for the speedometer component of the user interface:

```
     <div style={{ backgroundColor: '#282c34' }}>
          <GaugeComponent
              id="speedometer-gauge"
              arc={{
                nbSubArcs: 150,
                colorArray: ['#5BE12C', '#F5CD19', '#EA4228'],
                width: 0.025,
                padding: 0.003
              }}
              labels={{
                valueLabel: {
                  fontSize: 40,
                  formatTextValue: value => value + 'm/s'
                },
                tickLabels: {
                  type: "outer",
                  ticks: [
                    { value: 100 },
                    { value: 200 },
                    { value: 300 },
                    { value: 400 },
                    { value: 500 },
                    { value: 600 },
                    { value: 700 },
                    { value: 800 },
                    { value: 900 },
                    { value: 1000 },
                    { value: 1500 },
                    { value: 2000 },
                    { value: 2500 },
                    { value: 3000 },
                  ],
                  valueConfig: {
                    formatTextValue: value => value + 'm/s'
                  }
                }
              }}
              value={linSpeed}
              maxValue={3000}
          />
        </div>
```