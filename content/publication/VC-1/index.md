---
title: "Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Arjun Majumdar
- admin
- Sergio Arnaud
- Jason Ma
- Claire Chen
- Sneha Silwal
- Aryan Jain
- Vincent-Pierre Berges
- Tingfan Wu
- Jay Vakil
- Pieter Abbeel
- Jitendra Malik
- Dhruv Batra
- Yixin Lin
- Oleksandr Maksymets
- Aravind Rajeswaran
- Franziska Meier

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2023-12-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2023*
publication_short: In *Neurips*

abstract: "We present the largest and most comprehensive empirical study of pre-trained visual representations (PVRs) or visual 'foundation models' for Embodied AI. First, we curate CortexBench, consisting of 17 different tasks spanning locomotion, navigation, dexterous, and mobile manipulation. Next, we systematically evaluate existing PVRs and find that none are universally dominant.
To study the effect of pre-training data scale and diversity, we combine over 4,000 hours of egocentric videos from 7 different sources (over 5.6M images) and ImageNet to train different-sized vision transformers using Masked Auto-Encoding (MAE) on slices of this data. Contrary to inferences from prior work, we find that scaling dataset size and diversity does not improve performance universally (but does so on average).
Our largest model, named VC-1, outperforms all prior PVRs on average but does not universally dominate either. Finally, we show that task or domain-specific adaptation of VC-1 leads to substantial gains, with VC-1 (adapted) achieving competitive or superior performance than the best known results on all of the benchmarks in CortexBench. These models required over 10,000 GPU-hours to train and can be found on our website for the benefit of the research community."

# Summary. An optional shortened abstract.
summary: We present the largest and most comprehensive empirical study of visual foundation models for Embodied AI (EAI).

tags:
- Representation Learning
- Robot Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- name: NeurIPS 2023
  url:
- name: Blog
  url: https://ai.meta.com/blog/robots-learning-video-simulation-artificial-visual-cortex-vc-1/
url_pdf: 'https://arxiv.org/pdf/2303.18240.pdf'
url_code: 'https://github.com/facebookresearch/eai-vc'
url_dataset: 'https://github.com/facebookresearch/eai-vc/blob/main/cortexbench/DATASETS.md'
url_poster: ''
url_project: 'https://eai-vc.github.io/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Performance of VC-1 on CortexBench'
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