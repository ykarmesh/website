---
title: CiLQR for Motion Planning
summary: Constrained iLQR for Motion Planning in Autonomous Vehicles
tags:
- Robotics
- Vehicle Dynamics
date: "2019-11-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

url_code: "https://github.com/pparmesh/Constrained_ILQR"
url_pdf: "project/cilqr/16748_Report.pdf"
url_slides: "https://docs.google.com/presentation/d/1rjpu5S7Ky3r6FL81cYglspQL5Cb6vJXTn8HWY4RPWVk/edit?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In this project, we implemented an iterative Linear Quadratic Regulator (iLQR) algorithm that incorporates constraints in the environment for on-road autonomous motion planning. Since iLQR is based on the theory of dynamic programming, it does not inherently take constraints like obstacles, actuator limits, etc into account. Therefore a Constrained Iterative Linear Quadratic Regulator (CILQR) algorithm is used, which solves constrained optimal control problem in nonlinear systems efficiently. The algorithm is then deployed in an autonomous driving simulator, which is also be used for validation of the project.

You can find more information about the project here: [PDF](16748_Report.pdf). We also released the code for this project: [here](https://github.com/pparmesh/Constrained_ILQR)