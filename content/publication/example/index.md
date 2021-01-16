---
title: "La-MAML: Look-Ahead Meta-Learning for Continual Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Gunshi Gupta
- Liam Paull

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2020 (Oral)*
publication_short: In *Neurips*

abstract: The continual learning problem involves training models with limited capacity to perform well on a set of an unknown number of sequentially arriving tasks. While meta-learning shows great potential for reducing interference between old and new tasks, the current training procedures tend to be either slow or offline, and sensitive to many hyper-parameters. In this work, we propose Look-ahead MAML (La-MAML), a fast optimisation-based meta-learning algorithm for online-continual learning, aided by a small episodic memory. Our proposed modulation of per-parameter learning rates in our meta-learning update allows us to draw connections to prior work on hypergradients and meta-descent. This provides a more flexible and efficient way to mitigate catastrophic forgetting compared to conventional prior-based methods.La-MAML achieves performance superior to other replay-based, prior-based and meta-learning based approaches for continual learning on real-world visual classification benchmarks.

# Summary. An optional shortened abstract.
summary: In this work we develop a gradient-based meta-learning algorithm for efficient, online continual learning, that is robust and scalable to real-world visual benchmarks.

tags:
- Meta Learning
- Deep Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2007.13904.pdf'
url_code: 'https://github.com/montrealrobotics/La-MAML'
url_dataset: ''
url_poster: ''
url_project: 'https://mila.quebec/en/blog/'
url_slides: ''
url_source: 'https://papers.nips.cc/paper/2020/hash/85b9a5ac91cd629bd3afe396ec07270a-Abstract.html'
url_video: 'https://neurips.cc/virtual/2020/public/poster_85b9a5ac91cd629bd3afe396ec07270a.html'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'A pictoral depiction of the La-MAML algorithm'
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
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
