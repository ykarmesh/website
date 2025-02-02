---
title: "Pre-trained Text-to-Image Diffusion Models Are Versatile Representation Learners for Control"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Gunshi Gupta
- Karmesh Yadav
- Yarin Gal
- Dhruv Batra
- Zsolt Kira
- Cong Lu
- Tim G. J. Rudner

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-05-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2024*
publication_short: In *Neurips*

abstract: "Embodied AI agents require a fine-grained understanding of the physical world mediated through visual and language inputs. Such capabilities are difficult to learn solely from task-specific data. This has led to the emergence of pre-trained vision language models as a tool for transferring representations learned from internet-scale data to downstream tasks and new domains. However, commonly used contrastively trained representations such as in CLIP have been shown to fail at enabling embodied agents to gain a sufficiently fine-grained scene understanding—a capability vital for control. To address this shortcoming, we consider representations from pre-trained textto-image diffusion models, which are explicitly optimized to generate images from text prompts and as such, contain text-conditioned representations that reflect highly finegrained visuo-spatial information. Using pre-trained text-to-image diffusion models, we construct Stable Control Representations which allow learning downstream control policies that generalize to complex, open-ended environments. We show that policies learned using Stable Control Representations are competitive with state-of-the-art representation learning approaches across a broad range of simulated control settings, encompassing challenging manipulation and navigation tasks. Most notably, we show that Stable Control Representations enable learning policies that exhibit state-of-the-art performance on OVMM, a difficult open-vocabulary navigation benchmark."

# Summary. An optional shortened abstract.
summary: We investigate representations from pre-trained text-to-image diffusion models for control tasks and showcase competitive performance across a wide range of tasks.

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
- name: NeurIPS 2024
  url:
url_pdf: 'https://arxiv.org/pdf/2405.05852.pdf'
url_code: 'https://github.com/ykarmesh/stable-control-representations'
url_checkpoint: 'https://huggingface.co/ykarmesh/stable-control-representations'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://neurips.cc/virtual/2024/poster/95658'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'High-level overview of Stable Control Representations'
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