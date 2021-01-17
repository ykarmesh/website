---
title: "Learning to Prevent Monocular SLAM Failure using Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Vignesh Prasad
- admin
- Rohitashva Singh Saurabh
- Swapnil Daga
- Nahas Pareekutty
- K. Madhava Krishna
- Balaraman Ravindran
- Brojeshwar Bhowmick

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2018-12-23T00:00:00Z"
doi: "10.1145/3293353.3293400"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Indian Conference on Computer Vision, Graphics and Image Processing 2018*
publication_short: In *ICVGIP*

abstract: Monocular SLAM refers to using a single camera to estimate robot ego motion while building a map of the environment. While Monocular SLAM is a well studied problem, automating Monocular SLAM by integrating it with trajectory planning frameworks is particularly challenging. This paper presents a novel formulation based on Reinforcement Learning (RL) that generates fail safe trajectories wherein the SLAM generated outputs do not deviate largely from their true values. Quintessentially, the RL framework successfully learns the otherwise complex relation between perceptual inputs and motor actions and uses this knowledge to generate trajectories that do not cause failure of SLAM. We show systematically in simulations how the quality of the SLAM dramatically improves when trajectories are computed using RL. Our method scales effectively across Monocular SLAM frameworks in both simulation and in real world experiments with a mobile robot.

# Summary. An optional shortened abstract.
summary: In this work, we develop a novel formulation based on Reinforcement Learning (RL) that generates fail safe trajectories while using Monocular SLAM for localization.

tags:
- Reinforcement Learning
- Robotics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1607.07558'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=oPwjAYPFJf8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'One of the training environment for our algorithm'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to view the bibtex.
{{% /callout %}}
