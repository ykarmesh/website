---
title: Very Social Robot
summary: Learning Human-Robot Tool Handover using Interaction
tags:
- Robotics
- Manipulation
date: "2019-04-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: A handover interaction between Human and Robot
  focal_point: Smart

url_code: "https://github.com/dash-robotics"
url_pdf: "https://docs.google.com/document/d/1tIM2AM2Gf29-sXUYEU10nGkeHHjlOUO5cJ2qIVvNpCA/edit?usp=sharing"
url_slides: "https://docs.google.com/presentation/d/1pz75enG0ickIzulLCgeZ9WUNxDMdSOju0Na5tF5h4nQ/edit?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

We want to have robots assisting us throughout our daily activities, which often involve trivial pick and place, grasping, and handover use cases. However, these activities are still perceived by us as “robotic”. In our daily lives, we experience a variety of object handovers. Although the event of an object being transferred from one person to another seems trivial and happens subconsciously, it is a complex collaboration that involves verbal, visual, social and physical cues. It is important to us to develop and train robots in such a way that they are more reactive to humans, making the human-robot interaction seamless and efficient. Therefore, in this course project our aim was to develop more humanistic interaction strategies for a [Locobot](http://www.locobot.org/). 

I worked on the following modules:

* Created a planning and controls pipeline that was used for motion planning of the robot arm based on end-effector poses provided by the other modules. We used the Probabilistic RoadMap Planner for finding out collision free paths and PID controller for following the joint angle trajectories

![PRM_Planner](PRM_Planner.gif)

* Developed the module that predicted the best end-effector handover pose based on the rewards obtained from the interacting human.

Checkout our [Slides](https://docs.google.com/presentation/d/1pz75enG0ickIzulLCgeZ9WUNxDMdSOju0Na5tF5h4nQ/edit?usp=sharing) and [Report](https://docs.google.com/document/d/1tIM2AM2Gf29-sXUYEU10nGkeHHjlOUO5cJ2qIVvNpCA/edit?usp=sharing) for further details.