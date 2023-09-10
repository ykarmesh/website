---
title: "Offline visual representation learning for embodied navigation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Ram Ramrakhya
- Arjun Majumdar
- Vincent-Pierre Berges
- Sachit Kuhar
- Dhruv Batra
- Alexei Baevski
- Oleksandr Maksymets

# Author notes (optional)
author_notes: ''

date: "2022-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Reincarnating Reinforcement Learning Workshop at ICLR 2023*
publication_short: In *RRL at ICLR 2023*

abstract: How should we learn visual representations for embodied agents that must see and move? The status quo is tabula rasa in vivo, i.e. learning visual representations from scratch while also learning to move, potentially augmented with auxiliary tasks (e.g. predicting the action taken between two successive observations). In this paper, we show that an alternative 2-stage strategy is far more effective (1) offline pretraining of visual representations with self-supervised learning (SSL) using large-scale pre-rendered images of indoor environments (Omnidata (Eftekhar et al., 2021)), and (2) online finetuning of visuomotor representations on specific tasks with image augmentations under long learning schedules. We call this method Offline Visual Representation Learning (OVRL). We conduct largescale experiments – on 3 different 3D datasets (Gibson, HM3D, MP3D), 2 tasks (ImageNav, ObjectNav), and 2 policy learning algorithms (RL, IL) – and find that the OVRL representations lead to significant across-the-board improvements in state of art, on ImageNav from 29 2% to 54.2% (+25% absolute, 86% relative) and on ObjectNav from 18.1% to 23.2% (+5.1% absolute, 28% relative). Importantly, both results were achieved by the same visual encoder generalizing to datasets that were not seen during pretraining. While the benefits of pretraining sometimes diminish (or entirely disappear) with long finetuning schedules, we find that OVRL’s performance gains continue to increase (not decrease) as the agent is trained for 2 billion frames of experience.

# Summary. An optional shortened abstract.
summary: In this work we propose OVRL, a two-stage representation learning strategy for visual navigation tasks in Embodied AI.

tags:
- Embodied AI
- Representation Learning
- Deep Reinforcement Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=Spfbts_vNY'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://openreview.net/forum?id=Spfbts_vNY'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
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