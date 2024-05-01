---
title: "OpenEQA: Embodied Question Answering in the Era of Foundation Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Arjun Majumdar
- Anurag Ajay
- Xiaohan Zhang
- Pranav Putta
- Sriram Yenamandra
- Mikael Henaff
- Sneha Silwal
- Paul Mcvay
- Oleksandr Maksymets
- Sergio Arnaud
- admin
- Qiyang Li
- Ben Newman
- Mohit Sharma
- Vincent Berges
- Shiqi Zhang
- Pulkit Agrawal
- Yonatan Bisk
- Dhruv Batra
- Mrinal Kalakrishnan
- Franziska Meier
- Chris Paxton
- Sasha Sax
- Aravind Rajeswaran

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2024-04-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the *Conference on Computer Vision and Pattern Recognition 2024* and *ICRA Workshop on Mobile Manipulation and Embodied Intelligence, 2024 (Spotlight)*
publication_short: In *CVPR*

abstract: "We present a modern formulation of Embodied Question Answering (EQA) as the task of understanding an environment well enough to answer questions about it in natural language. An agent can achieve such an understanding by either drawing upon episodic memory, exemplified by agents on smart glasses, or by actively exploring the environment, as in the case of mobile robots. We accompany our formulation with OpenEQA - the first open-vocabulary benchmark dataset for EQA supporting both episodic memory and active exploration use cases. OpenEQA contains over 1600 high-quality human generated questions drawn from over 180 real-world environments. In addition to the dataset, we also provide an automatic LLM-powered evaluation protocol that has excellent correlation with human judgement. Using this dataset and evaluation protocol, we evaluate several state-of-the-art foundation models like GPT-4V and find that they significantly lag behind human-level performance. Consequently, OpenEQA stands out as a straightforward, measurable, and practically relevant benchmark that poses a considerable challenge to current generation of AI models. We hope this inspires and stimulates future research at the intersection of Embodied AI, conversational agents, and world models."

# Summary. An optional shortened abstract.
summary: We present a new embodied question answering (EQA) dataset with open vocabulary questions.

tags:
- Embodied AI

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- name: CVPR 2024
  url: 
url_pdf: 'https://open-eqa.github.io/assets/pdfs/paper.pdf'
url_code: 'https://github.com/facebookresearch/open-eqa'
url_dataset: 'https://github.com/facebookresearch/open-eqa?tab=readme-ov-file#dataset'
url_poster: ''
url_project: 'https://open-eqa.github.io/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: 
  caption: 'Interacting with an agent on OpenEQA dataset'
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