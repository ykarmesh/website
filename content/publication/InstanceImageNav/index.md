---
title: "Navigating to Objects Specified by Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jacob Krantz
- Theophile Gervet
- admin
- Austin Wang
- Chris Paxton
- Roozbeh Mottaghi
- Dhruv Batra
- Jitendra Malik
- Stefan Lee
- Devendra Singh Chaplot

# Author notes (optional)
# author_notes:

date: "2023-10-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision 2023*
publication_short: In *ICCV*

abstract: "Images are a convenient way to specify which particular object instance an embodied agent should navigate to. Solving this task requires semantic visual reasoning and exploration of unknown environments. We present a system that can perform this task in both simulation and the real world. Our modular method solves sub-tasks of exploration, goal instance re-identification, goal localization, and local navigation. We re-identify the goal instance in egocentric vision using feature-matching and localize the goal instance by projecting matched features to a map. Each sub-task is solved using off-the-shelf components requiring zero fine-tuning. On the HM3D InstanceImageNav benchmark, this system outperforms a baseline end-to-end RL policy 7x and a state-of-the-art ImageNav model 2.3x (56% vs 25% success). We deploy this system to a mobile robot platform and demonstrate effective real-world performance, achieving an 88% success rate across a home and an office environment."

# Summary. An optional shortened abstract.
summary: We present a modular system that can perform well on the Instance ImageNav task in both simulation and the real world.

tags:
- Embodied AI

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- name: ICCV 2023
  url: 
url_pdf: 'https://arxiv.org/pdf/2304.01192.pdf'
url_code: 'https://github.com/facebookresearch/home-robot/tree/main/projects/instanceimagenav'
url_dataset: ''
url_poster: ''
url_project: 'https://jacobkrantz.github.io/modular_iin'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=PexiA8P2ITM'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: 
  caption: 'Mod-IIN in the real world'
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