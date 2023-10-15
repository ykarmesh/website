---
title: "HomeRobot: Open-Vocabulary Mobile Manipulation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sriram Yenamandra
- Arun Ramachandran
- admin
- Austin S Wang
- Mukul Khanna
- Theophile Gervet
- Tsung-Yen Yang
- Vidhi Jain
- Alexander Clegg
- John M Turner
- Zsolt Kira
- Manolis Savva
- Angel X Chang
- Devendra Singh Chaplot
- Dhruv Batra
- Roozbeh Mottaghi
- Yonatan Bisk
- Chris Paxton

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2023-11-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Robot Learning 2023*
publication_short: In *CoRL*

abstract: "HomeRobot (noun): An affordable compliant robot that navigates homes and manipulates a wide range of objects in order to complete everyday tasks. Open-Vocabulary Mobile Manipulation (OVMM) is the problem of picking any object in any unseen environment, and placing it in a commanded location. This is a foundational challenge for robots to be useful assistants in human environments, because it involves tackling sub-problems from across robotics: perception, language understanding, navigation, and manipulation are all essential to OVMM. In addition, integration of the solutions to these sub-problems poses its own substantial challenges. To drive research in this area, we introduce the HomeRobot OVMM benchmark, where an agent navigates household environments to grasp novel objects and place them on target receptacles. HomeRobot has two components: a simulation component, which uses a large and diverse curated object set in new, high-quality multi-room home environments; and a real-world component, providing a software stack for the low-cost Hello Robot Stretch to encourage replication of real-world experiments across labs. We implement both reinforcement learning and heuristic (model-based) baselines and show evidence of sim-to-real transfer. Our baselines achieve a 20% success rate in the real world; our experiments identify ways future research work improve performance."

# Summary. An optional shortened abstract.
summary: We propose a combined simulation and real-world benchmark on the problem of Open-Vocabulary Mobile Manipulation (OVMM).

tags:
- Robot Learning
- Embodied AI

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- name: CoRL 2023
  url: 
url_pdf: 'https://arxiv.org/pdf/2306.11565.pdf'
url_code: 'https://github.com/facebookresearch/home-robot'
url_dataset: 'https://huggingface.co/ai-habitat'
url_poster: ''
url_project: 'https://ovmm.github.io/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=EA8HEzopkc0'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: 
  caption: 'Open-Vocabulary Mobile Manipulation requires agents to search for a previously unseen object at a particular location, and move it to the correct receptacle'
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